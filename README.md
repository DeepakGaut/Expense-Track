# Expense-Track

## 📌 Project Overview
Expense-Track is a **full-stack web application** that helps users track their expenses efficiently. It provides an intuitive UI for adding, viewing, and managing expenses, along with a backend API powered by **Node.js, Express, MongoDB, and Mongoose**.

## 🛠️ Tech Stack
- **Frontend:** React.js (if applicable)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Environment Management:** dotenv
- **Security & API Handling:** CORS

## 🚀 Features
- Add, update, delete, and view expenses.
- Store expense data in MongoDB.
- RESTful API architecture.
- Secure backend with Express and Mongoose.

## 📂 Folder Structure
```
Expense-Track/
│── backend/
│   ├── index.js          # Main server file
│   ├── routes/
│   │   ├── expense.js    # Expense-related API routes
│   ├── models/
│   │   ├── expense.js    # Mongoose schema for expenses
│   ├── .env              # Environment variables
│── frontend/ (if applicable)
│── README.md             # Project documentation
```

## 🔧 Installation & Setup
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/DeepakGaut/Expense-Track.git
cd Expense-Track
```
### **2️⃣ Setup Backend**
```sh
cd backend
npm install
```
### **3️⃣ Setup Environment Variables**
Create a `.env` file in the `backend/` directory:
```
DB=mongodb+srv://<username>:<password>@cluster0.mongodb.net/<database>?retryWrites=true&w=majority
PORT=5000
```
Replace `<username>`, `<password>`, and `<database>` with actual values.

### **4️⃣ Run the Backend**
```sh
npm start
```
If using **nodemon**, run:
```sh
npx nodemon index.js
```

## 📡 API Endpoints
### **1️⃣ Add an Expense**
```http
POST /api/v1/expenses
```
#### Request Body:
```json
{
  "title": "Grocery Shopping",
  "amount": 100,
  "category": "Food",
  "date": "2024-02-26"
}
```

### **2️⃣ Get All Expenses**
```http
GET /api/v1/expenses
```

### **3️⃣ Update an Expense**
```http
PUT /api/v1/expenses/:id
```
#### Request Body:
```json
{
  "title": "Dinner",
  "amount": 200
}
```

### **4️⃣ Delete an Expense**
```http
DELETE /api/v1/expenses/:id
```

## 📌 Future Improvements
- Add authentication for users.
- Implement data visualization.
- Build a frontend with React.js.

## 🎯 Contributing
Pull requests are welcome! Feel free to open an issue for feature requests or bug reports.
