# 🚀 ServiceSync

_ServiceSync is a web application for Customer Relationship Management (CRM) that connects requesters and service providers, facilitating problem resolution by automatically notifying the service provider._

_On Facebook, finding a professional to address your problem can require extensive searching and joining groups. In contrast, ServiceSync directly places your request on the service provider's dashboard, and you'll be notified when the right provider is available_

---

## 📸 Demo

[Live Demo](https://servicesync.onrender.com/)  

---

## ✨ Feature

1. ✅ Customer Management
      - Easily manage customer accounts, service requests, and communication.
2. ✅ Service Provider Tools
      - Streamline operations with powerful service management and tracking tools.
3. ✅ Admin Control
      - Comprehensive oversight and management of the entire service ecosystem.

---

## 🛠 Tech Stack

**Client:** React, Tailwind CSS  
**Server:** Node.js, Express  
**Database:** MongoDB  
**Other Tools:** Vite, Shadcn/UI

---

## 🚀 Getting Started
Follow the steps below to run the **ServiceSync** project locally:

### 🔁 1. Clone the repository

```bash
git clone https://github.com/yourusername/servicesync.git
cd servicesync
```

### 🔧 2. Set up the backend

a. Install dependencies
```bash
npm install
```

b. Create your `.env` file
Copy the sample environment file:
```bash
cp env-sample .env
```
> [!NOTE]
> ✍️ Edit the .env file and add your actual environment variables (e.g. MongoDB URI, JWT secret, etc.).

c. Run the backend server
```bash
npm run start
```
The backend will start on the port specified in your `.env` file (e.g., `http://localhost:5000`).

### 💻 3. Set up the frontend
Open a new terminal or tab, then:
```bash
cd frontend
```
a. Install dependencies
```bash
npm install
```
b. Run the frontend development server
```bash
npm run dev
```

The frontend will typically run at `http://localhost:5173/` (or whichever port Vite uses).



