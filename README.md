
# Expense Tracker

A full-stack Expense Tracker application designed to help users manage their finances efficiently. This app provides a user-friendly interface to track expenses, gain insights into spending patterns, and maintain a secure and personalized record of transactions.

## Features

- **Secure User Authentication:** Implements secure login and registration functionality to ensure user privacy.
- **CRUD Operations:** Enables users to create, read, update, and delete expenses with ease.
- **Real-Time Insights:** Provides detailed insights and analytics for better financial decision-making.
- **Responsive Design:** Ensures a seamless user experience across desktop and mobile devices.

## Technologies Used

### Frontend:
- **React.js:** For building an interactive and responsive user interface.
- **HTML, CSS:** For structuring and styling the application.
- **Bootstrap:** For responsive and visually appealing design.

### Backend:
- **Node.js & Express.js:** For developing a robust and scalable server-side application.

### Database:
- **MongoDB:** For storing user data and expense records securely.

## Setup and Installation

### Prerequisites:
- Node.js installed on your system.
- MongoDB database set up and running.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/DeepakGaut/Expense-Track.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Expense-Track
   ```
3. Install dependencies for the frontend:
   ```bash
   cd frontend
   npm install
   ```
4. Install dependencies for the backend:
   ```bash
   cd ../backend
   npm install
   ```
5. Configure environment variables:
   - Create a `.env` file in the `backend` directory and add your MongoDB connection string and other necessary variables.

6. Start the application:
   - Start the backend:
     ```bash
     npm start
     ```
   - Start the frontend:
     ```bash
     cd ../frontend
     npm start
     ```

### Accessing the App:
- Open your browser and go to `http://localhost:3000` to access the application.

## Project Structure
```
Expense-Track
├── frontend
│   ├── public
│   └── src
│       ├── components
│       ├── pages
│       └── styles
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   └── utils
└── README.md
```

## Contribution
Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your proposed changes.

## Contact
For any inquiries, please reach out to **Deepak Gautam** at [imdeepakgautam@gmail.com](mailto:imdeepakgautam@gmail.com).
