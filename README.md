# 📝 InstaBlog - Full Stack Blogging Platform  

InstaBlog is a feature-rich **Full Stack Blog Application** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**.  
It enables users to create, edit, and manage blog posts with secure authentication, a modern UI, and optimized APIs for seamless performance.  

🌐 **Live Demo**  
🔗 Live Site: https://instablog-swart.vercel.app  

---

## 🖼️ Screenshots  

🚪 **Landing Page**  

![Landing Page](https://raw.githubusercontent.com/Nayasha2003/Instablog-Public/75e539a43a0b1b97c7a8cee395df00b7367929ab/InstaBlog-Public/client/src/assets/1.png)


📝 **Blog Editor**  

![Published Blogs](https://raw.githubusercontent.com/Nayasha2003/Instablog-Public/75e539a43a0b1b97c7a8cee395df00b7367929ab/InstaBlog-Public/client/src/assets/2.png)


👤 **User Dashboard**  

![Subscription](https://raw.githubusercontent.com/Nayasha2003/Instablog-Public/75e539a43a0b1b97c7a8cee395df00b7367929ab/InstaBlog-Public/client/src/assets/3.png)


🔐 **Login Page**  

![Login Page](https://raw.githubusercontent.com/Nayasha2003/Instablog-Public/75e539a43a0b1b97c7a8cee395df00b7367929ab/InstaBlog-Public/client/src/assets/4.png)

---

## 💡 Features  

- 📝 Create, Edit, and Delete Blog Posts  
- 🔐 Secure JWT-based Authentication  
- 📚 View all published blogs in real-time  
- 👤 User dashboard to manage personal blogs  
- 🗂️ Blog search & category filtering  
- 📁 Cloud-based image uploads (ImageKit + Multer)  
- 🎨 Modern, responsive UI with TailwindCSS  
- ⚡ Optimized REST APIs with MongoDB schema design  
- 🚀 Less than **200ms response time** in local testing  

---

## 🛠 Tech Stack  

**Frontend:**  
- React.js  
- TailwindCSS  
- Axios  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB  
- Multer  
- ImageKit  

**Authentication:**  
- JWT (JSON Web Tokens)  

**Tools & Deployment:**  
- Vercel (Frontend)  
- Render/Heroku (Backend optional)  
- Git & GitHub  

---

## 📦 Installation & Setup  

### 📥 Clone the Repository  
```bash
git clone https://github.com/Nayasha2003/Instablog-Public.git
⚙️ Backend Setup

cd instablog-backend
npm install
Create a .env file in the backend root and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
IMAGEKIT_PUBLIC_KEY=your_imagekit_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_secret
Start the backend server:

npm start
The backend will run at http://localhost:5000.

🎨 Frontend Setup

cd ../instablog-client
npm install
Create a .env file in the frontend root and add:


VITE_BACKEND_URL=http://localhost:5000
Run the development server:


npm run dev
The frontend will run at http://localhost:5173.

🚀 Access the Application
Open your browser and go to http://localhost:5173.

Register/Login to create, edit, and manage your blog posts.

✨ Key Highlights
Secure and scalable full-stack blogging platform

Modern responsive UI for smooth user experience

Cloud-based media storage with ImageKit

Optimized API design for fast performance

