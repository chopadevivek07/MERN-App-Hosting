# MERN-App-Hosting
# MERN DALL-E Image Generation 🚀

![Frontend](https://img.shields.io/badge/Frontend-React-blue) 
![Backend](https://img.shields.io/badge/Backend-Node.js-green) 
![Database](https://img.shields.io/badge/Database-MongoDB-brightgreen) 
![Deployment](https://img.shields.io/badge/Deployment-AWS-orange) 

A full-stack MERN project that allows users to generate AI images using DALL-E and showcase them in a community gallery. Users can type prompts, generate images, save them, and explore other community creations.  

> **Focus:** This project demonstrates **AWS hosting, DevOps practices, and full-stack development**. It is hosted on an AWS EC2 instance with proper backend management, Nginx reverse proxy, and PM2 process control.  

---

## Table of Contents
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Project Overview](#project-overview)  
- [Installation & Setup](#installation--setup)  
- [Usage](#usage)  
- [Surprise Me Prompts](#surprise-me-prompts)  
- [Screenshots](#screenshots)  
- [DevOps & Cloud Deployment](#devops--cloud-deployment)  
- [Future Enhancements](#future-enhancements)  
- [Special Thanks](#special-thanks)  

---

## Features ✨
- Generate AI images from text prompts using the DALL-E API  
- Save generated images and prompts to MongoDB  
- Browse a community gallery of AI-generated images  
- Search posts by keywords  
- Responsive frontend built with React + Vite  
- Node.js + Express backend API  
- MongoDB database for persistent storage  
- Hosted on AWS EC2 with Nginx reverse proxy  
- PM2 process manager for reliable backend  
- “Surprise Me” button to generate random creative prompts  

---

## Tech Stack 🛠️
- **Frontend:** React, Vite, Tailwind CSS (optional)  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  
- **Deployment / DevOps:** AWS EC2, Nginx, PM2, Environment Variables, Process Monitoring  

---

## Project Overview 📖
This project is a practical full-stack application integrating modern web technologies with AI, with a strong focus on **cloud deployment and DevOps practices**.  

### Frontend
- Interactive React interface  
- Type prompts manually or use “Surprise Me”  
- View AI-generated images immediately in the gallery  

### Backend
- Express server handles API routes:  
  - `/api/v1/post` → CRUD operations for posts  
  - `/api/v1/dalle` → Sends prompts to DALL-E API and returns generated images  

### Database
- MongoDB stores all posts including prompt, image URL, and timestamp  

### Deployment / DevOps
- Hosted on **AWS EC2** for hands-on cloud experience  
- Nginx serves frontend and proxies backend API requests  
- PM2 ensures backend runs continuously  
- Environment variables secure sensitive API keys  
- Node.js app monitored and auto-restarted using PM2  
- Demonstrates end-to-end DevOps workflow: setup → deployment → monitoring  

---

## Installation & Setup ⚙️
1. Clone the repository  
2. Configure the backend:  
   - Install dependencies  
   - Add `.env` with MongoDB URI and OpenAI API Key  
   - Start backend using Node.js or PM2  
3. Configure the frontend:  
   - Install dependencies  
   - Build frontend for production  
   - Deploy build files to Nginx web directory  
4. Configure Nginx to serve frontend and proxy backend API  
5. Restart Nginx and ensure backend is running  

---

## Usage 🚀
- Open the project in a browser via EC2 public IP or domain  
- Click **Create**, type a prompt, or click **Surprise Me**  
- Generated images appear instantly and save to the community gallery  
- Use search bar to filter posts by keywords  

---

## Surprise Me Prompts 🎨
Some example prompts for the “Surprise Me” button:  
- A glowing castle floating in the clouds, fantasy art  
- A magical forest with bioluminescent mushrooms at night  
- A cyberpunk city with flying cars and neon lights, 3D render  
- A panda riding a skateboard in a city park  
- A dragon flying over a volcano, cinematic scene  
- A cup of coffee with steam forming a dragon, artistic  

---

## Screenshots 🖼️

![Homepage](/imaages/Screenshot%20(379).png)  
![](/imaages/Screenshot%20(380).png)  
![](/imaages/Screenshot%20(381).png)  

---

## PowerShell / Terminal Commands 💻

Here are some key commands executed during deployment and development on AWS EC2. You can replace these with screenshots to showcase your workflow.

### 1. Cloning the Repository
- connecting to the server
![](/imaages/Screenshot%20(358).png)
- Installing Node JS
![](/imaages/Screenshot%20(362).png)
- Installing Mongodb org 
![](/imaages/Screenshot%20(366).png)
- Mongodb Status
![](/imaages/Screenshot%20(368).png)
- Npm install 
![](/imaages/Screenshot%20(370).png)
- Creating build folder
![](/imaages/Screenshot%20(370).png)
- Installing PM2
![](/imaages/Screenshot%20(371).png)
![](/imaages/Screenshot%20(373).png)
- Installing NGINX web server
![](/imaages/Screenshot%20(375).png)
![](/imaages/Screenshot%20(376).png)
![](/imaages/Screenshot%20(378).png)



## DevOps & Cloud Deployment ☁️
- Hosted on **AWS EC2** for real-world cloud deployment experience  
- **Nginx** used as a reverse proxy for frontend and backend routing  
- **PM2** ensures backend Node.js process stays online and restarts on failure  
- **Environment Variables** used for sensitive keys (MongoDB, OpenAI)  
- Demonstrates **end-to-end DevOps workflow**: server setup → deployment → monitoring → production-ready  

---

## Future Enhancements 🚧
- User authentication & profiles  
- Like/comment system for posts  
- Pagination & filters in gallery  
- Support multiple AI models  

---

## Special Thanks 🙏
Special thanks to my mentors and guides who helped me throughout this project.  
