# 🩸 Blood Bank WebApp

A full-stack **MERN (MongoDB, Express, React, Node.js)** web application that manages blood donations and transactions.  
This system enables hospitals, donors, organizations, and admins to collaborate seamlessly for efficient blood bank management.

---

## 🚀 Features

- **Authentication & Authorization**
  - Secure login & registration
  - Role-based access control: `Admin`, `Organisation`, `Donor`, `Hospital`

- **Donor Management**
  - Donors can register and specify the amount of blood they wish to donate or withdraw
  - Donation/withdrawal requests are tracked

- **Hospital & Organisation Features**
  - Hospitals can view blood transactions from donors
  - Hospitals verify and approve blood donations
  - Organisations manage blood availability across multiple hospitals

- **Transaction History**
  - All blood donation and withdrawal activities are recorded
  - Role-specific dashboards to track activity

- **Backend APIs**
  - RESTful APIs built using **Express.js & Node.js**
  - CRUD operations for users, roles, and transactions

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Redux, TailwindCSS / CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Mongoose ODM)  
- **Authentication**: JWT (JSON Web Tokens)  

---


## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/blood-bank-webapp.git
cd blood-bank-webapp
