# 💳 Online Banking System

A web-based banking application that enables users to manage their accounts, perform transactions, and view real-time account details — built using Java, Spring Boot, MySQL, and basic front-end technologies.

---

## 🛠️ Tech Stack

- **Backend**: Java, Spring Boot  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: MySQL  
- **Tools**: Maven, Eclipse/VS Code, Git

---

## ✨ Features

- 🔐 **User Authentication** (Register/Login/Logout)
- 🧾 **View Account Details** (Balance, Name, Account Number)
- 💸 **Fund Transfer** (Send money to other users)
- 📜 **Transaction History** (All past debit/credit activities)
- 🧑‍💼 **Admin Panel** (Manage Users & Accounts)
- ✅ Form Validations & Error Handling
- 🔒 Password Encryption (Optional)

---

## 📁 Folder Structure (Example)


OnlineBankingSystem/
├── src/
│ ├── main/
│ │ ├── java/com/bank/controller/
│ │ ├── java/com/bank/model/
│ │ ├── java/com/bank/repository/
│ │ ├── java/com/bank/service/
│ │ └── java/com/bank/OnlineBankingApplication.java
│ ├── resources/
│ │ ├── application.properties
│ │ └── templates/
│ │ ├── login.html
│ │ ├── dashboard.html
│ │ └── transfer.html
└── pom.xml

yaml
Copy
Edit

---

## 🗃️ Database Schema (Basic Tables)

- **User Table**: Stores user info (ID, Name, Email, Password, Balance)
- **Transaction Table**: Stores transactions (ID, SenderID, ReceiverID, Amount, Timestamp)
- **Admin Table** *(optional)*

---

## 🚀 How to Run

1. Clone this repository  
   `git clone https://github.com/your-username/online-banking-system.git`

2. Import into your IDE (Eclipse or VS Code)

3. Configure MySQL database in `application.properties`

4. Run the application using Spring Boot (`OnlineBankingApplication.java`)

5. Open browser and go to:  
   `http://localhost:8080`
