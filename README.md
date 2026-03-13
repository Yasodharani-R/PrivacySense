**#PrivacySense - Enterprise-Wide Personal Data Discovery & Classification (DPDPA-Aligned)
**
**## Project Overview**
This project is a secure enterprise web application designed to discover, classify, and manage personal data across organizational systems in compliance with the Digital Personal Data Protection Act, 2023.

Organizations often store sensitive personal data in multiple locations such as internal databases, employee systems, and cloud storage. This system helps identify where personal data exists, classify it based on sensitivity, and control access using role-based permissions.

The platform improves data visibility, security monitoring, and regulatory compliance.



**## Features**

- Role-based authentication system
- Three user roles: Admin, Manager, Employee
- Admin-controlled user account creation
- Personal data discovery and classification
- Encrypted storage of sensitive data
- Activity logs (login time, location, device information)
- Cloud database integration using Firebase
- Compliance-focused reporting
  
**## Technologies Used**

*Frontend*
- React
- Next.js
- Tailwind CSS

*Backend*
- Node.js

*Database & Cloud*
- Firebase

*AI Integration*
- Google Gemini API

*Development Tools*
- Visual Studio Code
- npm (Node Package Manager)

*Environment Management*
- .env configuration for API keys

  
**## System Roles**

**### Admin**
- Creates and manages user accounts
- Full access to system data
- Generates compliance reports

**### Manager**
- Views classified data reports
- Monitors system activity

**### Employee**
- Restricted system access
- Limited operational functions
- Restricted system access
- Limited operational functions


**## Setup Instructions**

Follow these steps to run the project locally.

**### Install Required Software**

Make sure the following are installed:

- Node.js (v18 or higher)
- Visual Studio Code

Check Node version:

- node -v

**### Open the Project**

1. Open *Visual Studio Code*
2. Click *File → Open Folder*
3. Select the project folder (*PrivacySense*)

You should see the following files and folders:

- src
- docs
- node_modules
- package.json
- tailwind.config.ts
- .env

**### Install All Dependencies**

Open the terminal in VS Code:

*Terminal - New Terminal*

Run the following command:

- npm install

This installs the libraries used by the project such as:

- React
- Next.js
- Tailwind CSS
- Firebase

**### Add Environment Variables**

This project uses *Gemini AI from Google*.

Open the .env file and add:

GEMINI_API_KEY=your_api_key

Without this key, the AI features may not work properly.

**### Run the Application**

Run the following command:
-npm run dev

**### Open the Dashboard**

Open your browser and go to:
http://localhost:3000

if following any issues delete the following folders:
- node_modules
- .next

then run again 
npm install npm run day 

**## Usage**

1. Login using credentials created by the Admin.
2. Admin can create users and manage system access.
3. Managers can view data classification and reports.
4. Employees can access limited system functions.
5. The system logs user activities and stores encrypted data securely in the cloud.



**## Live Demo**

Project Link  
https://9000-firebase-studio-1773416352399.cluster-htdgsbmflbdmov5xrjithceibm.cloudworkstations.dev


**## Future Improvements
**
- AI-based automatic personal data detection
- Risk scoring for exposed sensitive data
- Automated compliance alerts
- Integration with enterprise cloud storage systems
