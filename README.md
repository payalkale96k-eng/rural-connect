🌾 Rural Connect

Rural Connect is a web-based platform designed to provide useful information and digital services for rural communities.

The platform brings important rural-related information into one place, including government schemes, agriculture, market information, opportunities, weather, announcements, alerts, complaints, and user services.

✨ Features

- 🏠 Home Page
  
  - Introduction to Rural Connect
  - Easy navigation to different services

- 🏛️ Government Schemes
  
  - Browse available government schemes
  - View scheme details and eligibility information

- 🌱 Agriculture
  
  - Agriculture-related information
  - Useful information and resources for farmers

- 🛒 Market Information
  
  - View available market information
  - Access useful information for rural users

- 💼 Opportunities
  
  - View available opportunities
  - Access information about opportunities relevant to rural communities

- 🌦️ Weather
  
  - View weather information
  - Weather data can be provided through the weather API

- 📢 Announcements
  
  - View important announcements
  - Keep users updated with new information

- 🚨 Alerts
  
  - Display important alerts and notifications

- 📝 Complaint Management
  
  - Users can submit complaints
  - Users can view their complaints
  - Users can track complaint details

- 👤 User Account
  
  - User registration
  - User login
  - User profile
  - User dashboard
  - User notifications

- 👨‍💼 Admin Dashboard
  
  - Manage users
  - Manage schemes
  - Manage agriculture information
  - Manage announcements
  - Manage alerts
  - Manage opportunities
  - Manage complaints
  - View analytics

🛠️ Technologies Used

Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap

Backend

- Node.js
- Express.js
- REST APIs
- JWT Authentication

Data Storage

The current project uses a JSON-based data storage system:

Backend/data/rural-connect.json

📁 Project Structure

RuralConnect/<br/>
│<br/>
├── frontend/<br/>
│   ├── index.html<br/>
│   ├── about.html<br/>
│   ├── login.html<br/>
│   ├── register.html<br/>
│   ├── agriculture.html<br/>
│   ├── market.html<br/>
│   ├── opportunities.html<br/>
│   ├── schemes.html<br/>
│   ├── scheme-detail.html<br/>
│   ├── weather.html<br/>
│   │<br/>
│   ├── dashboard/<br/>
│   │   ├── user-dashboard.html<br/>
│   │   ├── profile.html<br/>
│   │   ├── my-complaints.html<br/>
│   │   ├── submit-complaint.html<br/>
│   │   ├── complaint-detail.html<br/>
│   │   └── notifications.html<br/>
│   │<br/>
│   ├── admin/
│   │   ├── admin-dashboard.html<br/>
│   │   ├── users.html<br/>
│   │   ├── schemes.html<br/>
│   │   ├── agriculture.html<br/>
│   │   ├── announcements.html<br/>
│   │   ├── alerts.html<br/>
│   │   ├── opportunities.html<br/>
│   │   ├── complaints.html<br/>
│   │   └── analytics.html<br/>
│   │<br/>
│   ├── css/<br/>
│   └── js/<br/>
│<br/>
├── Backend<br/>
│   ├── server.js<br/>
│   ├── seed.js<br/>
│   ├── package.json<br/>
│   ├── package-lock.json<br/>
│   ├── .env.example<br/>
│   ├── data/<br/>
│   │   └── rural-connect.json<br/>
│   └── uploads/<br/>
│<br/>
├── package.json<br/>
├── package-lock.json<br/>
├── .gitignore<br/>
└── README.md<br/>

💻 Requirements

Before running the project, install:

- Node.js
- npm
- A modern web browser

Check Node.js:

node --version

Check npm:

npm --version

🔑 Authentication

Rural Connect provides user authentication using:

- User registration
- User login
- JWT authentication
- Protected user routes
- Admin authentication
- Role-based access

👤 User Features

Registered users can access their personal dashboard.

The dashboard provides features such as:

- Profile
- Complaints
- Notifications
- Available schemes
- Agriculture information
- Market information
- Opportunities
- Announcements
- Alerts

👨‍💼 Admin Features

The administrator can manage the information displayed on the platform.

Admin functionality includes:

- User management
- Scheme management
- Agriculture management
- Announcement management
- Alert management
- Opportunity management
- Complaint management
- Analytics

📊 Data Storage

The current version stores application data in:

Backend/data/rural-connect.json

The project includes a seed script for initializing the demo data.

Run:

npm run seed

to initialize the data.

🔌 API

The frontend communicates with the backend using REST APIs.

Some of the main API areas include:

/api/auth
/api/users
/api/schemes
/api/agriculture
/api/market
/api/opportunities
/api/announcements
/api/alerts
/api/complaints
/api/notifications
/api/weather

The backend also provides a health-check endpoint:

/api/health

🌐 Deployment

The project can be deployed using a separate frontend and backend setup.

Backend

The Node.js backend can be deployed on platforms such as:

- Render
- Railway
- Other Node.js hosting platforms

Typical backend settings:

Root Directory: Backend
Build Command: npm install
Start Command: npm start

Environment variables such as "JWT_SECRET" and "OPENWEATHER_API_KEY" should be added through the hosting platform's environment-variable settings.

Frontend

The frontend consists of HTML, CSS, and JavaScript files and can be deployed using platforms such as:

- Netlify
- Vercel
- GitHub Pages 

The frontend API configuration should point to the deployed backend URL.

🔄 Updating the Project

After making changes to the project:

git add .

Create a commit:

git commit -m "Update project"

Push the changes:

git push

🧪 Troubleshooting

Backend does not start

Try:

npm install

Then:

npm start

Website cannot connect to the backend

Check that the backend is running and test:

http://localhost:5000/api/health

Weather is not working

Check that:

OPENWEATHER_API_KEY

is correctly configured in "Backend/.env".

Login is not working

Check:

- Backend is running
- Database/data file is available
- Required environment variables are configured
- Browser console for frontend errors

🎯 Project Objective

The main objective of Rural Connect is to provide a simple digital platform where rural users can access important information and services from one place.

The project focuses on improving access to:

- Government schemes
- Agriculture information
- Market information
- Weather information
- Opportunities
- Announcements
- Alerts
- Complaint services

📌 Project Status

Project Type: Web Application

Status: Academic / Demonstration Project

Rural Connect is currently designed as an academic and demonstration project. The current version uses JSON-based data storage and can be further enhanced with a production database and additional security features.

📄 License

This project is created for educational and demonstration purposes.

---

🌾 Rural Connect

Connecting Rural Communities with Information and Services.
