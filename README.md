# Expense-Track

## Overview
Expense-Track is a web application designed to help users efficiently manage and track their expenses. With an intuitive user interface, users can add, edit, and delete expenses, categorize them, and visualize their spending habits over time.

## Features
- Add, edit, and delete expenses
- Categorize expenses (e.g., Food, Travel, Bills, Entertainment, etc.)
- View expense history
- Graphical representation of expenses
- User authentication and secure login
- Responsive design for mobile and desktop

## Technologies Used
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (via MongoDB Atlas)
- **Authentication:** JWT (JSON Web Tokens)
- **State Management:** Context API / Redux (if applicable)

## Installation
To set up the project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Expense-Track.git
   cd Expense-Track
   ```

2. Install dependencies for the backend and frontend:
   ```sh
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `backend` directory with the following:
     ```sh
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

4. Start the backend server:
   ```sh
   cd backend
   npm start
   ```

5. Start the frontend application:
   ```sh
   cd frontend
   npm start
   ```

6. Open the application in your browser at `http://localhost:3000/`.

## Usage
- Sign up or log in to your account
- Add expenses with a description, amount, and category
- View expenses in a list or graphical format
- Edit or delete transactions as needed
- Securely log out when finished

## Contributing
If you would like to contribute to this project, follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-name`)
3. Make your changes and commit them (`git commit -m 'Add new feature'`)
4. Push to your fork (`git push origin feature-name`)
5. Open a Pull Request

## Author
**Deepak Gautam**
