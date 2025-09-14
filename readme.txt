
===============================================================
                    EventSphere - README
===============================================================

Project Name: EventSphere
Team Name: SFC-Code Avengers
React version: 19.1
Tech Stack: MERN (React, Node.js) + MySQL
website git repo url : npm run dev

===============================================================
TEAM MEMBERS
===============================================================
1. M.Taqi Adeem         
2. Syed Mehdi      
3. M.Faiez   
4. Raheel 

===============================================================
1. PROJECT DESCRIPTION
===============================================================
EventSphere is a full-stack college event management platform designed
to streamline the process of planning, managing, and participating in
college events. The platform supports multiple roles such as:
- Admin
- Organizer
- Participant (Student)

Key Features:
- Event listing (upcoming, ongoing, past events)
- Event registration and cancellation
- Dynamic seat management and waitlist
- QR-based attendance
- Media gallery for event photos/videos
- Certificate download
- Feedback and ratings
- Real-time notifications
- Role-based dashboards

===============================================================
2. DEFAULT LOGIN CREDENTIALS
===============================================================
Admin:
  Email: admin@eventsphere.com
  Password: Abcd@1234

Organizer:
  Email: organizer@eventsphere.com
  Password: Abcd@1234

Participant:
  Email: mehdi123@gmail.com
  Password: 98765

===============================================================
5. INSTALLATION STEPS
===============================================================
Follow these steps to run EventSphere locally.


Step 1: Install Dependencies
--------------------------------
For Backend:
cd backend
npm install

For Frontend:
cd frontend
npm install

Step 2: Configure MySQL Database
--------------------------------
1. Open MySQL Workbench or phpMyAdmin.
2. Create a new database named: eventsphere
3. Import the SQL dump located in:
   database/eventsphere.sql

Step 3: Configure Environment Variables
--------------------------------
Create a `.env` file in the backend folder with the following:
--------------------------------
PORT=5000
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=
DB_NAME=eventsphere_

--------------------------------

Step 4: Run the Project
--------------------------------
# Run Frontend 
npm install
npm run dev

#Run backend
cd server
npm run

=============================================================

Database Hosting:
- Host MySQL 

3. COLOR THEME (UI)
background color: white
textcolor : purple and white

COLOR THEME
Sidebar : black
background color : white