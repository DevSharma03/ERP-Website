# ERP Website  

## 🚀 Overview  
The **ERP Website** is a comprehensive Enterprise Resource Planning (ERP) system designed to optimize business processes. It includes modules for inventory management, finance, employee management, and analytics, ensuring smooth departmental communication and efficiency.  

## 🛠 Tech Stack  
- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT, OAuth (Google Login)  
- **Deployment:** Vercel (Frontend), Render/AWS/GCP (Backend), MongoDB Atlas  
- **Other Tools:** Redux, REST APIs, CI/CD (GitHub Actions)  

## ✨ Features  
✅ **User Management** – Role-based access control (Admin, Employee, Manager)  
✅ **Inventory Management** – Real-time stock tracking  
✅ **Finance & Accounting** – Expense, invoice, and payment management  
✅ **Employee Portal** – Payroll, attendance tracking, HR tools  
✅ **Dashboard & Analytics** – Data visualization for insights  
✅ **Secure Authentication** – JWT and OAuth-based login  
✅ **Cloud Deployment** – Scalable and optimized for production  

## 📂 Project Structure  
```
ERP-Website/
│-- frontend/       # React.js frontend code
│-- backend/        # Express.js backend code
│-- database/       # MongoDB models and configurations
│-- public/         # Static assets
│-- .env.example    # Example environment variables
│-- package.json    # Dependencies and scripts
│-- README.md       # Project documentation
```  

## 🚀 Getting Started  

### Prerequisites  
Ensure you have:  
- Node.js (>=16.x)  
- MongoDB (local/cloud)  
- Git  

### Installation  
Clone the repository:  
```sh
git clone https://github.com/DevSharma03/ERP-Website.git
cd ERP-Website
```  

#### Backend Setup  
```sh
cd backend
npm install
npm run dev  # Starts backend server
```  

#### Frontend Setup  
```sh
cd frontend
npm install
npm start  # Runs frontend on localhost:3000
```  

### 🔑 Environment Variables  
Create a `.env` file in the backend directory:  
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
OAUTH_CLIENT_ID=your_google_client_id
OAUTH_CLIENT_SECRET=your_google_client_secret
```  

## 🛠 Deployment  
- **Frontend:** Vercel/Netlify  
- **Backend:** AWS, GCP, Render  
- **Database:** MongoDB Atlas  

## 🤝 Contributing  
Contributions are welcome! Feel free to open issues or submit PRs.  

## 📜 License  
This project is licensed under the **MIT License**.  

## 📞 Contact  
- **Devashish Sharma**  
- 📧 Email: devsharma@example.com  
- 🌐 [LinkedIn](https://linkedin.com/in/devsharma03) | [GitHub](https://github.com/DevSharma03)  
