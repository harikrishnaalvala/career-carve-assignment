

## Overview

CareerCarve provides placement training to MBA students through various activities, including the 1x1 Mock Interview session. This project is designed to create an automated and user-friendly scheduler for students and mentors to book and manage their 1x1 sessions efficiently. Built with modern technologies such as React+Vite, Clerk, Neon, and Express, this project emphasizes a seamless experience for both students and mentors.

## Features

### Student Features

- **Home Screen**
  - Overview of available services.
  - Quick access to schedule a 1x1 session.
  - Notifications about upcoming sessions or new features.
  
- **Login/Registration Page**
  - Secure sign-up and login options.
  - Option to link with college email or other verification methods.
  
- **Profile Page**
  - Manage personal information and preferences.
  - Select area of interest and preferred mentors.
  
- **Schedule Session Page**
  - **Area of Interest Selection**: Choose an area (e.g., FMCG Sales, Equity Research).
  - **Mentor Selection**: Auto-assign or select a specific mentor.
  - **Availability Checker**: Display available slots based on both student and mentor availability.
  - **Duration Selection**: Choose session length (30, 45, or 60 minutes).
  
- **Payment Page**
  - Display cost based on session duration and mentor selection.
  - Secure payment gateway integration.
  
- **Confirmation Page**
  - Summary of the scheduled session.
  - Add session to personal calendar.
  
- **My Sessions Page**
  - View upcoming and past sessions.
  - Option to reschedule or cancel sessions.
  
- **Notifications**
  - Reminders for upcoming sessions.
  - Updates on any changes or cancellations.
  
- **Feedback Page**
  - Provide feedback on the session and mentor.

### Mentor Features

- **Home Screen**
  - Overview of upcoming and past sessions.
  - Notifications about student bookings or changes.
  
- **Login/Registration Page**
  - Secure login options with profile verification.
  
- **Profile Page**
  - Manage personal information and expertise.
  - Set availability and area(s) of interest.
  
- **Availability Management Page**
  - Set and update available time slots.
  - Set preferences for back-to-back sessions.
  
- **Session Schedule Page**
  - View and manage upcoming sessions.
  - Option to accept or reschedule sessions.
  
- **Notifications**
  - Alerts for new bookings or changes.
  - Reminders for upcoming sessions.
  
- **Feedback Page**
  - View feedback from students.
  - Provide feedback on student sessions.

### Shared Features

- **Booking Management**
  - Real-time synchronization to avoid double bookings.
  - Automated conflict resolution based on priority rules.
  
- **Calendar Integration**
  - Sync with Google Calendar, Outlook, etc., for both students and mentors.
  
- **Automated Reminders**
  - Notifications sent via email/SMS for upcoming sessions, payment confirmations, and changes.
  
- **User Support**
  - Help section or chat support for troubleshooting and queries.

## Tech Stack

### Frontend

- **React + Vite**: Blazing-fast development with modern frontend tools.
- **Clerk**: User authentication and management.
- **Tailwind CSS**: For styling and responsive design.
- **Moment.js**: Handling dates and times.

### Backend

- **Express**: Node.js web framework for building the API.
- **Neon**: PostgreSQL as a Service, for managing and querying the database.
- **Axios**: For making HTTP requests from the frontend to the backend.

### Deployment

- **Vercel**: Hosting and deployment for the frontend.


## Setup and Installation

### Prerequisites

- Node.js (>= 14.x)
- npm or yarn
- PostgreSQL (via Neon or local instance)

### Installation Steps

1. **Clone the Repository**:
   ```bash
   https://github.com/harikrishnaalvala/career-carve-assignment.git
   
   cd careercarve
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```



4. **Run the Development Server**:
   - **Frontend**:
     ```bash
     npm run dev
     ```


5. **Access the App**:
   - Frontend: `http://localhost:5173`


