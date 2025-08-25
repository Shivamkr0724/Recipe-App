# 👨‍🍳 TastyTrove

An AI-powered recipe suggestion web application built with **Vite + React**.  
Just provide the ingredients you have, and the app uses **Mistral AI (via Hugging Face Inference API)** to generate creative recipe ideas you can cook right away!

---

## 🚀 Features

- 🔹 Enter ingredients you have at home
- 🔹 Get instant recipe suggestions from **Mistral AI via Hugging Face**
- 🔹 Clean and responsive UI built with **React + Vite**
- 🔹 Lightweight and fast

---

## 🛠️ Tech Stack

- **Frontend:** React, Vite
- **AI Model:** Mistral AI (Hugging Face Inference API)

---

## ⚙️ Installation & Setup

**Prerequisites**

Make sure you have the following installed on your machine:

- **[Git](https://git-scm.com/)**
- **[Node.js](https://nodejs.org/en)**
- **[npm](https://www.npmjs.com/)** _(Node Package Manager)_

**Cloning the Repository**

```bash
git https://github.com/Shivamkr0724/TastyTrove.git
cd TastyTrove
```

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
VITE_HF_ACCESS_TOKEN=your_api_key_here
```

Replace the placeholder values with your actual credentials by signing up on the **[HuggingFace](https://huggingface.co/)** dashboard.

**Running the Project**

```bash
npm run dev
```
