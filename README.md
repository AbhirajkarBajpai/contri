# Contri: Expense Splitting Platform

Contri is a web application designed to simplify expense splitting among friends or group members. It offers intuitive features for creating groups, tracking expenses, and managing custom splits, ensuring a seamless experience for users. Built using the MERN stack, Contri prioritizes responsiveness, security, and ease of use.

---

## Features

### Frontend:

- **Dynamic User Interface:** Built with **ReactJS** for a responsive and engaging user experience.
- **State Management:** Leveraged **Redux** to handle complex state updates, ensuring a smooth workflow for users.
- **Responsive Design:** Designed with modern CSS techniques to provide a seamless experience across devices.
- **Expense Management:** Allows users to input expenses, select participants, and view detailed split summaries.
- **Custom Split Functionality:** Provides the option to manually adjust expense distributions for unique scenarios.

### Backend:

- **Authentication and Authorization:** Implemented secure user login and route protection using **JWT tokens**.
- **Scalable Architecture:** Built with **Node.js** and **Express** for robust and efficient backend services.
- **API Design:** Developed RESTful APIs to enable seamless interaction between the frontend and backend.
- **Middleware Usage:** Added middleware for validation, error handling, and logging.

### Key Functionalities:

- **Group Management:** Users can create groups by entering their friends' phone numbers, with invitations sent automatically.
- **Expense Tracking:** Tracks individual and group expenses, with real-time updates on total splits.
- **Custom Splitting:** Allows manual adjustments for scenarios like extra contributions by a member.
- **Protected Routes:** Ensures data security with authenticated API access.

---

## Tech Stack

- **Frontend:** ReactJS, Redux, CSS
- **Backend:** Node.js, Express
- **Authentication:** JWT (JSON Web Tokens)
- **Database:** MongoDB

---

## Installation

### Prerequisites:

- Node.js and npm installed on your machine.
- MongoDB server running locally or remotely.

### Steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/AbhirajkarBajpai/contri.git
   ```
2. Navigate to the project directory:
   ```bash
   cd contri
   npm install
   ```
3. Install dependencies for the backend:
   ```bash
   cd ../Backend
   npm install
   ```
4. start/connect to your MongoDB server
5. Configure environment variables in .env file (for backend):
   ```bash
   PORT=5000
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   JWT_SECRET=your_jwt_secret(on you)
   ```
6. Start the backend server:
   ```bash
   npm run start
   ```
7. Start the frontend server:
   ```bash
   cd ../frontend
   npm start
   ```
8. Access the application at http://localhost:3000.

### Usage Flow

- **Sign Up/Login:** Create an account or log in using your credentials.

- **Create Groups:** Enter your friends' phone numbers to form a group. Invitations will be sent automatically.
- **Add Expenses:** Log expenses and select group members to split with.
- **Adjust Splits:** Use the manual adjustment feature for uneven contributions.
- **View Summaries:** Check detailed split information and track expenses in real-time.

---

### Future Enhancements

- **Integration with Payment Gateways:** Allow users to settle balances directly through the webapp.
- **Notifications:** Enable email and sms notifications for updates and reminders.

---

### Contributions

Contributions are welcome! Please fork the repository and create a pull request with your changes.

---

### Contact

For any questions or feedback, please reach out to abhirajkarbajpai2707@gmail.com.
