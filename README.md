# UpLift Website

**UpLift Website** is a MERN-stack-based charity platform designed to empower communities by bridging the gap between donors, volunteers, and beneficiaries. Our goal is to facilitate charitable activities, amplify awareness for causes, and streamline the management of donations and volunteer efforts, all within a seamless and secure digital ecosystem.

---

## Key Features

- **Donation System:** Secure and efficient payment processing using **Xendit** for monetary contributions.  
- **Volunteer Management:** Tools to register, organize, and manage volunteers for events and activities.  
- **Cause Awareness:** Showcase impactful campaigns, success stories, and initiatives through blogs and media.  
- **User-Friendly Interface:** Intuitive design to ensure easy access for all users.  
- **Responsive Design:** Fully optimized for devices of all sizes.  

---

## Technologies Used

- **Frontend:** React.js  
- **Backend:** Node.js with Express.js  
- **Database:** Supabase (PostgreSQL)  
- **Payment Integration:** Xendit for secure and localized payment solutions  

---

## Mission

The UpLift Website is dedicated to connecting people with opportunities to make a difference. By leveraging modern web technologies, we aim to create a user-friendly platform that uplifts communities and fosters positive change.

---

## Getting Started

Follow these steps to set up the project locally:

### Prerequisites

Ensure you have the following installed on your system:
- Node.js and npm
- Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/apexeldevelopment/UpLift-Website.git
2. **Navigate to the project directory:**
   ```bash
   cd uplift-website
3. **Install dependencies for both frontend and backend:**
   ```bash
   cd client && npm install
   cd ../server && npm install
4. **Set up environment variables:**
   - Create a .env file in the server directory and add the following:
     ```bash
     SUPABASE_URL=your-supabase-url
     SUPABASE_KEY=your-supabase-key
     XENDIT_SECRET_KEY=your-xendit-secret-key
   - Similarly, in the client directory, configure environment variables if needed.
5. **Run the application:**
   - Start the backend server:
     ```bash
     cd server && npm run dev
   - Start the frontend development server:
     ```bash
     cd client && npm start
6. **Access the application:**
   - Open your browser and navigate to http://localhost:3000 to view the frontend.
   - The backend API will be running on http://localhost:5000.
  
---

## Directory Structure

The directory structure of the project is as follows:

uplift-website/
├── client/         # React frontend
├── server/         # Node.js backend
├── README.md       # Project documentation
└── .gitignore      # Git ignore file
