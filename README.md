# 🧠 Promptopia — AI Prompt Sharing Platform

This project is a modern, full-stack web application built using **Next.js 14**, inspired by  
the excellent tutorial from [JavaScript Mastery (YouTube)](https://www.youtube.com/@javascriptmastery)  
and the original repository by [Adrian Hajdin](https://github.com/adrianhajdin/project_next_14_ai_prompt_sharing).

I followed the tutorial closely and made changes to support **Next.js App Router (v15)** and updated dependencies, giving me my first hands-on experience with modern Next.js and full-stack development.

It was a great milestone in my learning journey and gave me the confidence to build full-stack projects on my own going forward.

---

## 📚 Table of Contents

1. [📖 Introduction](#-introduction)
2. [⚙️ Tech Stack](#️-tech-stack)
3. [🚀 Features](#-features)
4. [⚡ Quick Start](#-quick-start)
5. [🧠 What I Learned](#-what-i-learned)
6. [🙌 Credits](#-credits)

---

## 📖 Introduction

**Promptopia** is a full-stack AI prompt sharing platform where users can:
- Share, edit, and delete their own AI prompts
- Discover prompts shared by others
- Explore creator profiles
- Search prompts by tag
- Copy prompts easily with one click

It implements secure authentication using **NextAuth**, connects to **MongoDB**, and follows modern React/Next.js coding patterns.

---

## ⚙️ Tech Stack

- [Next.js 15](https://nextjs.org/)
- [React](https://react.dev/)
- [MongoDB](https://www.mongodb.com/)
- [NextAuth.js](https://next-auth.js.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [App Router](https://nextjs.org/docs/app/building-your-application/routing)
- CSS Modules, Client/Server Components

---

## 🚀 Features

- 💡 **Create, Read, Update, and Delete (CRUD)** AI prompts  
- 🌐 **Google Authentication** via NextAuth  
- 🖼️ **User profile pages** with their own prompt lists  
- 🔍 **Search prompts by tag**  
- 🧷 **Copy-to-clipboard** support  
- 🤝 **View other users’ profiles**  
- 📱 **Fully responsive design (mobile + desktop)**  
- ✨ **Modern UI with Glassmorphism styling**  
- 🧩 Reusable components and clean architecture  

---

## ⚡ Quick Start

### 🧰 Prerequisites

Make sure you have the following installed:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [pnpm](https://pnpm.io/)

---

### 🔽 Clone the Repository

```bash
git clone https://github.com/hemantsinghdev/promptopia-sharing-platform
cd promptopia-sharing-platform
````

---

### 📦 Install Dependencies

```bash
npm install
# or
pnpm install
```

---

### 🔐 Set Up Environment Variables

Create a `.env` file in the root directory and add:

```env
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=your_random_secret
GOOGLE_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
MONGODB_URI=your_mongo_connection_string
```

> Get credentials from:
>
> * [Google Cloud Console](https://console.cloud.google.com/)
> * [Random secret generator](https://www.cryptool.org/en/cto/openssl)
> * [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

---

### ▶️ Run the Development Server

```bash
npm run dev
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 🧠 What I Learned

This was my **first full-stack project with Next.js**, and it helped me learn:

* How the **App Router** architecture works in Next.js 15
* Managing both **client and server components**
* Implementing **authentication with NextAuth**
* Connecting to **MongoDB** using Mongoose
* Using **Tailwind CSS** for styling a modern UI
* Building clean folder structures and reusable components
* Understanding real-world full-stack flows: from request → DB → response

This project gave me the **confidence to build more full-stack apps independently**.

---

## 🙌 Credits

* Original project repo: [github.com/adrianhajdin/project\_next\_14\_ai\_prompt\_sharing](https://github.com/adrianhajdin/project_next_14_ai_prompt_sharing)
* Tutorial by [JavaScript Mastery (YouTube)](https://www.youtube.com/@javascriptmastery)

---

> Made with learning and a growing love for full-stack development 🚀
> by [**Hemant Singh**](https://github.com/hemantsinghdev)
