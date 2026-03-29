# 🚀 NxtBuild – AI Web App Builder

Turn your ideas into real websites using AI. Just describe what you want… and boom, it builds it 🪄

---

## 🧠 What is this?

NxtBuild is a full-stack app where you can:

* 💬 Describe a website in plain English
* 🤖 AI (Gemini) generates full code
* 👀 See a live preview instantly
* 💾 Save your projects

Basically… idea → working app in seconds ✨ 

---

## 🧩 Features

* 🔐 Login & Signup (secure auth)
* 📁 Project dashboard
* 🤖 AI code generation (HTML/CSS/JS)
* 💬 Chat-based builder
* 👀 Live preview
* 📥 Download your code

---

## 🛠️ Tech Stack

* Frontend: React + Vite
* Backend: Node.js + Express
* Database: MongoDB Atlas
* AI: Google Gemini

---

## 📁 Project Structure

```
root/
 ├── client/     → frontend (React)
 └── server/     → backend (Node + Express)
```

---

## ⚙️ Setup (Super Simple)

### 1. Clone the repo

```
git clone https://github.com/your-username/nxtbuild.git
cd nxtbuild
```

---

### 2. Setup Backend

```
cd server
npm install
```

#### 🔑 Create `.env` file inside `/server`

Copy this:

```
MONGODB_URI=your_mongodb_atlas_url
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
```

### What these mean:

* `MONGODB_URI` → your database link (from MongoDB Atlas)
* `JWT_SECRET` → any random text (used for login security)
* `GEMINI_API_KEY` → your Google Gemini API key

---

### 3. Start Backend

```
npm run dev
```

(or `node server.js`)

---

### 4. Setup Frontend

```
cd ../client
npm install
```

---

### 5. Start Frontend

```
npm run dev
```

---

## 🌐 Running the App

* Frontend → http://localhost:5173
* Backend → http://localhost:5000

---

## 🚀 Deployment (No Localhost Needed)

### Backend → Render / Railway

### Frontend → Vercel

Steps:

* Upload code to GitHub
* Add environment variables on hosting
* Replace `localhost` with your backend URL

---

## ❗ Important Notes

* Never share your `.env` file
* Always use environment variables (no hardcoding keys)
* Allow MongoDB Atlas access (`0.0.0.0/0`)

---

## 🧪 How it Works (Simple)

1. You type: *“make me a portfolio website”*
2. AI understands it
3. AI generates full code
4. App shows preview
5. You edit → AI improves it

---

## 💡 Example

You:

> "Make a landing page with a navbar and hero section"

App:
✔ Creates full HTML
✔ Adds styling
✔ Makes it responsive

---

## 🤝 Contributing

Feel free to fork, improve, and build your own version 💙

---

## 📌 Final Thought

This project removes the hardest part of coding: **starting**

Now you just think… and build 🚀
