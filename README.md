<div align="center">

# ONECLICK AI ⚡

Your Ultimate AI Assistant for Content Creation and Image Editing

![Last Commit](https://img.shields.io/github/last-commit/elyse502/QuickAI?style=flat-square) 
![Languages](https://img.shields.io/github/languages/top/elyse502/QuickAI?style=flat-square&color=blue)
![License](https://img.shields.io/badge/license-ISC-blue?style=flat-square)
![Version](https://img.shields.io/badge/version-1.0.0-success?style=flat-square)

*Harnessing modern tech for smarter workflows:*  

![React](https://img.shields.io/badge/React-19.1.1-61DAFB?style=flat-square&logo=react&logoColor=black)
![Express](https://img.shields.io/badge/Express-5.1.0-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

🌐 **Try it Live:** [_OneClick AI Demo_](https://one-click-ai-phi.vercel.app/)

</div>

---

## What is OneClick AI?

OneClick AI is a versatile platform that combines AI-powered tools for content creation and image manipulation in one place. Whether you want to generate images, write blog posts, or optimize your resume, OneClick AI gives you the tools to do it instantly.  

- Generate high-quality images from text prompts  
- Remove backgrounds or unwanted objects from images  
- Write articles or create blog titles with AI assistance  
- Analyze and improve resumes with AI recommendations  
- Share your creations with a growing community  

Built using the **PERN stack** (PostgreSQL, Express, React, Node.js) and integrated with **OpenAI's AI models**, OneClick AI is fast, scalable, and user-friendly.  

---

## Features at a Glance

### AI Tools
- **Image Generation** – Create visuals from your text ideas  
- **Background Removal** – Cleanly remove image backgrounds  
- **Object Removal** – Remove unwanted elements seamlessly  
- **Article Writing** – AI-assisted content creation  
- **Blog Titles** – Generate catchy, optimized titles  
- **Resume Review** – Get AI suggestions for improvement  

### User-Friendly Design
- **Secure Login** – Powered by Clerk authentication  
- **Interactive Dashboard** – Access all tools from a single hub  
- **Community Sharing** – Showcase and explore creations  
- **Responsive UI** – Optimized for desktops and mobile  
- **Real-Time Results** – Instant AI processing  

### Enterprise-Ready
- **File Management** – Upload and process images securely with Cloudinary  
- **PDF Support** – Analyze resumes in PDF format  
- **Scalable Backend** – Handles high traffic efficiently  
- **API-First Design** – Fully RESTful backend  

---

## Tech Stack

**Frontend**
- React 19  
- Vite for fast builds  
- Tailwind CSS  
- React Router DOM  
- Axios  
- React Hot Toast  
- React Markdown  
- Clerk for authentication  
- Lucide React icons  

**Backend**
- Node.js + Express 5  
- PostgreSQL (via Neon)  
- OpenAI API  
- Cloudinary for media storage  
- Multer for file uploads  
- CORS for cross-origin requests  
- PDF-Parse for text extraction  

**Deployment**
- Vercel (frontend)  
- Render/Vercel (backend)  
- Neon (PostgreSQL hosting)  
- Cloudinary (media CDN)  

---

 
### Installation

1. Clone the repo:
```console
git clone https://github.com/Monusingh0009/OneClick-AI.git
cd OneClick-AI
```

2. Install client dependencies:
```console
cd client && npm install
```

3. Install server dependencies:
```console
cd ../server && npm install
```

4. Set environment variables

**Client (.env)**
```console
VITE_CLERK_PUBLISHABLE_KEY=pk_test_...
VITE_API_BASE_URL=http://localhost:3000
```

**Server (.env)**
```env
OPENAI_API_KEY=sk-your-openai-key
CLOUDINARY_CLOUD_NAME=your-cloud-name
CLOUDINARY_API_KEY=your-api-key
CLOUDINARY_API_SECRET=your-api-secret
DATABASE_URL=your-postgres-connection-string
CLERK_SECRET_KEY=sk_test_...
PORT=5000
```

5. Start servers:
```console
# Backend
cd server && npm run server

# Frontend
cd client && npm run dev

```

## AI Capabilities

### 🎨 Image Generation
- Turn text into stunning visuals
 
### 🖼️ Image Editing
- Remove backgrounds and objects effortlessly
 
### 📝 Content Creation
- Generate articles and blog titles with AI guidance

### 📄Resume Analysis
- Get actionable suggestions and scoring
- Skills gap identification
- Improvement recommendations
- PDF text extraction

---

## Deployment

### Frontend:
- Vercel

### Backend: 
- Render or Vercel

### Database: 
- Neon PostgreSQL

### Media: 
- Cloudinary

### Authentication: 
- Clerk
 

</div>




