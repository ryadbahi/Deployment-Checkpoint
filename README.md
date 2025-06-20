# MERN Recipe App Deployment — Alternative to Azure


## ⚠️ Deployment Note

Due to an unresolved issue with my **GitHub Student Pack Azure account**, I was **unable to deploy to Microsoft Azure** as originally required.  
However, I completed the full deployment using **free-tier cloud services** that meet the same technical criteria:

- ✅ Cloud-hosted backend
- ✅ Cloud MongoDB database (Atlas)
- ✅ Public frontend accessible from any device

---

## 🌐 Live Demo

- **Frontend (Vercel)**: [Here](https://deploy-checkpoint-frontend.vercel.app/)
- **Backend (Render)**: [Here](https://deploy-checkpoint-backend.onrender.com/api/recipes/test)

---

## 🛠 Tech Stack

- **Frontend**: Vite + React + TailwindCSS + TypeScript
- **Backend**: Node.js + Express
- **Database**: MongoDB Atlas
- **Deployment**:
  - 🌐 **Frontend**: [Vercel](https://vercel.com)
  - ☁️ **Backend**: [Render](https://render.com)
  - 🛢 **Database**: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

---

## 🚀 Features

- Add and list recipes (title, ingredients, steps)
- Stores data on MongoDB Atlas
- React frontend fetches from Express API
- Fully cloud-deployed and accessible
