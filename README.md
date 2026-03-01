TrustFund: A Transparent Crowdfunding & Donation System
TrustFund is a fully functional full-stack web application designed to provide a secure, transparent, and structured platform for crowdfunding and donations. The system enables users to create fundraising campaigns, contribute securely, and monitor transaction history in real time.
The application follows a modular architecture with a clearly separated backend and frontend, ensuring scalability, maintainability, and clean code organization.
System Overview
The application is built using a layered architecture consisting of:
A Node.js and Express-based backend API
A responsive frontend interface
MongoDB database for persistent data storage
RESTful routes for fund and transaction management
Middleware for validation and error handling
PayPal integration for secure online transactions
The backend manages campaign creation, donation processing, and transaction tracking, while the frontend provides a user-friendly dashboard for interaction. Secure payment processing is implemented using PayPal to ensure reliable and protected financial transactions.
Features
Create and manage crowdfunding campaigns
Secure online donations using PayPal
Real-time transaction tracking
Transparent record management
RESTful API architecture
Structured MVC-based backend design
Modular controllers, routes, and middleware
Fully functional end-to-end workflow
Technology Stack
Backend:
Node.js
Express.js
JavaScript
Frontend:
HTML
CSS
JavaScript
Database:
MongoDB
Payment Gateway:
PayPal
Version Control:
Git
GitHub
Installation and Setup
Clone the repository:
git clone https://github.com/your-username/TRUSTFUND.git
cd TRUSTFUND
Install backend dependencies:
cd trustfund-backend
npm install
Configure environment variables:
Create a .env file inside the backend folder and add:
PORT=5000
MONGO_URI=your_mongodb_connection_string
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_CLIENT_SECRET=your_paypal_secret
Start the backend server:
npm start
Run the frontend:
Open the frontend folder and launch the application using a local development server or directly open the main HTML file in your browser.
Future Enhancements
User authentication and role-based access control
Admin dashboard for monitoring campaigns
Automated financial reporting
Cloud deployment and scalability improvements
Enhanced analytics and visualization tools
Author
Krish Yadav
B.Tech Computer Science Engineering