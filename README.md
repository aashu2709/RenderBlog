# 📰 RenderBlog

A full-stack blogging platform built with **React**, **Vite**, **Appwrite**, and **Tailwind CSS**, designed to offer a modern and seamless experience for writing, publishing, and managing blog posts. This platform allows users to register, create, edit, and delete blog posts, with secure media uploads and real-time content editing using a rich-text editor.

---

## ✨ Features

- 🧠 User authentication (Sign up / Login / Logout)
- ✍️ Rich text editor (TinyMCE) for writing blog content
- 📤 Upload and preview featured images via Appwrite Storage
- 📃 Create, update, and delete posts
- 📰 View all published blog posts
- 🔐 Protected routes for authenticated users
- 🧭 Dynamic routing for individual blog pages
- 🌐 Fully responsive design with Tailwind CSS

---

## ⚙️ Tech Stack

- **Frontend**: React, Vite, Tailwind CSS, React Hook Form, Redux Toolkit
- **Backend/Service**: Appwrite (Authentication, Database, Storage)
- **Editor**: TinyMCE
- **Routing**: React Router v6

---

## 🛠️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/aashu2709/RenderBlog.git
cd RenderBlog
```
### 2. Install dependencies

```bash
npm install
# or
yarn install
```
### 3. Configure environment variables
Create a .env file in the root directory and add the following variables with your actual Appwrite and TinyMCE credentials:
```bash
VITE_APPWRITE_URL=https://<your-appwrite-endpoint>
VITE_APPWRITE_PROJECT_ID=<your-project-id>
VITE_APPWRITE_DATABASE_ID=<your-database-id>
VITE_APPWRITE_COLLECTION_ID=<your-collection-id>
VITE_APPWRITE_BUCKET_ID=<your-bucket-id>
VITE_TINYMCE_API_KEY=<your-tinymce-api-key>
```
⚠️ Ensure your Appwrite project allows connections from your development URL (e.g. http://localhost:5173) by setting the platform under Project Settings → Platforms.
