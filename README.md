1. Clone the repository:
   ```bash
   git clone https://github.com/AbhirajkarBajpai/contri.git
2. Navigate to the project directory:
   ```bash
   cd contri
   npm install
4. Install dependencies for the backend:
   ```bash
   cd ../Backend
   npm install
5. start/connect to your MongoDB server
6. Configure environment variables in .env file (for backend):
   ```bash
   PORT=5000
   MONGO_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   JWT_SECRET=your_jwt_secret(on you)
7. Start the backend server:
   ```bash
   npm run start
8. Start the frontend server:
   ```bash
   cd ../frontend
   npm start
9. Access the application at http://localhost:3000.


### Usage Flow

- **Sign Up/Login:** Create an account or log in using your credentials.

- **Create Groups:** Enter your friends' phone numbers to form a group. Invitations will be sent automatically.
- **Add Expenses:** Log expenses and select group members to split with.
- **Adjust Splits:** Use the manual adjustment feature for uneven contributions.
- **View Summaries:** Check detailed split information and track expenses in real-time.
---
### Future Enhancements
- **Integration with Payment Gateways:** Allow users to settle balances directly through the webapp.
- **Notifications:**  Enable email and sms notifications for updates and reminders.
---
### Contributions
Contributions are welcome! Please fork the repository and create a pull request with your changes.
---
### Contact
For any questions or feedback, please reach out to abhirajkarbajpai2707@gmail.com.