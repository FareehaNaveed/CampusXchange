# 🚀 CampusXchange  
### Exchange Smart, Live Smart

CampusXchange is a **student-focused marketplace and skill-sharing platform** designed to simplify buying, selling, and learning within a trusted community.

---

## 🌟 Overview

CampusXchange allows students to:

- 📚 Buy & sell used books, gadgets, furniture  
- 🎓 Access free and premium learning content  
- 💬 Chat privately with buyers/sellers  
- 🛡️ Experience a secure, admin-controlled system  

---

## 🧠 Core Features

### 🔐 Authentication System
- Email & password login
- Persistent login session
- Dynamic UI (Login → Profile Avatar)

---

### 🛒 Marketplace
- Upload listings (title, price, image)
- Listings go through **admin approval**
- Only approved listings are visible publicly
- Clean responsive card layout

---

### 🛡️ Admin Dashboard
- View all pending listings
- Approve or reject submissions
- Full visibility over platform activity

---

### 💬 Private Chat System
- Buyer ↔ Seller communication
- Real-time messaging (Firestore)
- No phone number exposure

---

### 🎓 Skill Hub
- Free & Pro learning sections
- Tab-based switching system
- Scalable for LMS integration

---

### 👤 User Profile
- Displays user email
- Shows user's listings and status
- Avatar generated from initials

---

## ⚙️ Tech Stack

| Layer        | Technology |
|-------------|-----------|
| Frontend    | HTML, Tailwind CSS, JavaScript |
| Backend     | Firebase (Auth, Firestore, Storage) |
| Hosting     | Vercel |
| Icons       | Lucide Icons |
| Font        | Inter |


---

## 🔥 Firebase Setup

### 1. Create Project
- Go to Firebase Console  
- Create a new project  

---

### 2. Enable Authentication
- Go to Authentication → Sign-in Method  
- Enable **Email/Password**  

---

### 3. Firestore Database

Create collections:

listings
users
messages


---

### 4. Firestore Data Structure

#### 📦 listings

{
title: string,
price: string,
image: string,
userId: string,
status: "pending" | "approved"
}

#### 👤 users

{
email: string,
isPro: boolean
}


#### 💬 messages

{
chatId: string,
text: string,
sender: string,
time: timestamp
}


---

### 5. Storage (Optional)
- Store listing images in Firebase Storage  

---

## 🧪 How It Works

### 🛒 Marketplace Flow

User uploads → status = "pending"
Admin approves → becomes visible


---

### 💬 Chat Flow

Buyer clicks "Contact Seller"
→ Chat created
→ Messages stored in Firestore
→ Real-time updates


---

### 🔐 Admin Access
Admin email:


fariyaghul@gmail.com


---

## 🚀 Deployment (Vercel)

1. Push project to GitHub  
2. Import repository into Vercel  
3. Deploy  

---

## ⚠️ Known Issues

- Marketplace UI needs refinement  
- Admin dashboard visuals can improve  
- Skill hub interaction polishing required  
- Payment system not implemented yet  

---

## 🔮 Future Improvements

- 💳 Stripe payment integration (Pro upgrade)  
- 🔔 Real-time notifications  
- 📊 Advanced admin analytics  
- 📱 Progressive Web App (PWA)  
- 🎥 Video streaming for Skill Hub  

---

## 👨‍💻 Author

**Fareeha Naveed **  
Student Developer & Entrepreneur  

---

## 📜 License

This project is for educational and entrepreneurial use.

---

## 💡 Vision

To build a **trusted, student-first ecosystem** where learning and exchange are seamless, affordable, and secure.

---

