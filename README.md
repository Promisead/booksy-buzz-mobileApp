
#<h1 align="center">📚 Booksy Buzz – Full‑Stack React Native Application 🚀</h1>

![Demo App](/mobile/assets/images/screenshot-for-readme.png)

## 🎯 Project Overview

**Booksy Buzz** is a comprehensive **full-stack** mobile application built with React Native and powered by a robust Node.js backend.

- ✅ Compatible with **real devices** and **emulators** (Android / iOS)  
- ✅ Built entirely with **JavaScript**—no native code or paid services required  
- ✅ Entire project can be completed in approximately **7 hours**

---

## 🧑‍💻 Key Features

- 🔐 **Authentication** – User registration and login using JWT, with error handling for invalid credentials  
- 🏠 **Home Feed** – Displays posts in reverse chronological order with **infinite scrolling**  
- ➕ **Create Post** – Add posts with a title, rating, cover image, and caption (all fields required)  
- 👤 **User Profile** – View user details along with their created posts  
- 🗑️ **Post Deletion** – Includes confirmation prompt before deleting a post  
- 🎨 **Theming Support** – Switch between **4 pre-built themes** effortlessly  
- 🌐 **Web Compatibility** – Can run in a browser via `localhost`  
- 🚪 **Logout Functionality**

---

## 🧠 Pinned highlightd

- ⚙️ How to build a REST API using **Node.js**, **Express**, and **MongoDB**  
- 🔐 Implement **stateless authentication** using **JSON Web Tokens (JWT)**  
- 🔄 Efficient **infinite pagination** with cursor-based loading  
- 🖼️ Handle image uploads using **base64 encoding** and **Cloudinary**  
- 🛠️ Deploy your backend for **free** using platforms like **Render** or **Railway**  
- 📱 Develop a cross-platform mobile app using **React Native** and **Expo Router**  
- 🧭 Add animated transitions and shared element navigation  
- 🧪 Test and debug directly on a physical device—**no need for Android Studio or Xcode**

---

## 🔧 Environment Setup

### Backend Configuration (`/backend`)

Create a `.env` file with the following variables:

```bash
PORT=3000
MONGO_URI=<YOUR_MONGO_DB_URI>
JWT_SECRET=<YOUR_SECURE_SECRET>

CLOUDINARY_CLOUD_NAME=<YOUR_CLOUDINARY_CLOUD_NAME>
CLOUDINARY_API_KEY=<YOUR_CLOUDINARY_API_KEY>
CLOUDINARY_API_SECRET=<YOUR_CLOUDINARY_API_SECRET>

API_URL=<YOUR_DEPLOYED_API_ENDPOINT>
