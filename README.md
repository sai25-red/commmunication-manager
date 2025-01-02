# Communication Tracker

Communication Tracker is a React-based web application designed to help businesses manage and track communications with various companies. The application provides features for logging communications, scheduling follow-ups, maintaining a comprehensive company database and also provide notification for over due communication.

## Github Link
https://github.com/sai25-red/commmunication-manager

## Deployment Link
https://commmunication-manager-feuy6vjl8-sais-projects-f4e5b7bd.vercel.app

## Prerequisites
* Node.js (v16.0.0 or later)

* npm (v8.0.0 or later)

* A modern web browser

## Setup and Installation

Use the package manager npm to install Communication Tracker.

## 1. Clone the Repository

```bash
git clone https://github.com/sai25-red/commmunication-manager

cd ENTNT-communicationTracking
```

## 2. Install Dependencies

```bash
npm install
```
## 3. Run the Application
```bash
# Development Mode
npm start

# Production Build
npm run build
```

## Deployment

**vercel**

To deploy this project run
```bash
npm run build
```

Then Upload build file to vercel

## Application Functionality

**Key Features**

* **Dashboard Views**
    * Overview of communication status for each company
    * Users can select a specific company or multi-select multiple companies to log communication and 
    * When hovering over a completed communication, a tooltip will display the notes or comments recorded for that communication.

  
* **Admin Module**
    * Add new companies
    * Manage communication methods

   

* **Calendar View**
    * View Past Communications
    * View and manage Upcoming Communications

   
   
* **Company List**
    * View All the companies
    * Edit and delete companies

   

* **Notification**
    * The notification icon display a badge with the count of overdue and due communications
    * View all overdue and due communications by clicking the icon
 


## Known Limitations
* No built-in authentication system
* Relies on client-side state management
* No persistent data storage (requires backend integration)

## Technology Stack
* React.js
* React Router
* Context API for state management
* Lucide React for icons
* CSS for styling
* used react-big-calendar for calendar view

## Future Roadmap
* Implement user authentication
* Add backend database integration
* Develop reporting and analytics features


## License
This project has been bulid by Gaddam saicharan

## Contact
saicharan25102001@gmail.com

Deployed Project Link: https://github.com/sai25-red/commmunication-manager


