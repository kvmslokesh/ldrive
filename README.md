# 🚀 LDRive – The Professional's Cloud

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)  
![Next.js](https://img.shields.io/badge/Next.js-15-000000?logo=next.js&logoColor=white)  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38B2AC?logo=tailwind-css&logoColor=white)  
![Appwrite](https://img.shields.io/badge/Appwrite-Cloud-F02E65?logo=appwrite&logoColor=white)

LDRive is a **modern storage management and file sharing platform** that lets users effortlessly upload, organize, and share files.  
Built with **React 19**, **Next.js 15**, **Tailwind CSS**, and the **Appwrite Node SDK**, it leverages the latest features for **seamless file management** and a smooth user experience.

---

## ✨ Features

- 🔐 **User Authentication with Appwrite** – Signup, login, and logout.
- 📤 **File Uploads** – Upload documents, images, videos, audio, and more.
- 📂 **View & Manage Files** – Browse files, open in a new tab, rename, or delete.
- ⬇️ **Download Files** – Instant file downloads.
- 🔗 **File Sharing** – Share files with others easily.
- 📊 **Dashboard** – Total storage, consumed storage, recent uploads, file type breakdown.
- 🔎 **Global Search** – Quickly find files across the platform.
- ↕️ **Sorting Options** – Sort by date, name, or size.
- 💻 **Modern Responsive UI** – Clean, minimalist, and responsive with Tailwind CSS.
- ⚡ **Cutting-edge Stack** – React 19, Next.js 15, and Appwrite with reusable code architecture.

---

## 🛠️ Tech Stack

- **Frontend**: React 19, Next.js 15, Tailwind CSS
- **Backend/Services**: Appwrite Node SDK
- **Deployment**: Vercel / Any Next.js compatible hosting

---

## ⚙️ Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/LDRive.git
cd LDRive
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Configure Appwrite

Go to Appwrite Console.
Create a new Project (copy the Project ID).

Inside the project:

Create a Database (copy the Database ID).

Inside the database, create:

- A Users Collection (copy its Collection ID).
- A Files Collection (copy its Collection ID).

Go to Storage → Create a Bucket (copy its Bucket ID).

Go to API Keys → Create a key with access to:

- Authentication
- Database (for your collections)
- Storage (for your bucket)
- Users

Add these values into .env.local:

```bash
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://fra.cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT="your_project_id"
NEXT_PUBLIC_APPWRITE_DATABASE="your_database_id"
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION="your_users_collection_id"
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION="your_files_collection_id"
NEXT_PUBLIC_APPWRITE_BUCKET="your_bucket_id"
NEXT_APPWRITE_KEY="your_api_key"
```

### 4️⃣ Run Locally
```bash
npm run dev
```
App will be running at: <a href="http://localhost:3000" target="_blank">http://localhost:3000</a>

<p align="center">
  <a href="https://ldrive.netlify.app" target="_blank">
    🌍 <b>Live Demo – LDRive</b> 🚀
  </a>
</p>
