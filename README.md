# Mobile Esports Tournament Frontend

This is the frontend of the mobile esports tournament app, built using React and styled with Tailwind CSS. It allows users to view tournaments, register teams, track match schedules, and manage user profiles.

## Setup

### 1. Clone the repository

Clone the repository to your local machine by running:
git clone https://github.com/kppetrick/mobile-esports-tournament-frontend.git

### 2. Navigate to the project directory
Go into the project folder:

bash
Copy code
cd mobile-esports-tournament-frontend

### 3. Install dependencies
Install all the required project dependencies:

bash
Copy code
npm install

### 4. Tailwind CSS Setup
Ensure that Tailwind CSS is set up correctly by following the necessary setup steps. If Tailwind is not yet installed or configured, you can follow the installation guide from Tailwind CSS Documentation.

After setting up, ensure the following files exist in your project:
tailwind.config.js
postcss.config.js
These files will allow you to customize the Tailwind setup and use PostCSS for processing styles.

### 5. Start the development server
Once the dependencies are installed, run the app in development mode:

bash
Copy code
npm start
This will open the app in your default browser at http://localhost:3000. Any changes you make to the code will be reflected immediately as the app is running in hot-reload mode.

### Usage
Once the app is running, you can expect the following functionalities:

Tournament Overview: A list of upcoming and ongoing tournaments, with the ability to join as a player or team.
Team Registration: Teams can register for tournaments, update their roster, and manage their team details.
Match Schedule: View upcoming match times and details, and track the progress of live matches.
Profile Management: Users can manage their profiles, view past tournament participation, and update personal information.
Directory Structure
Here’s an overview of the project’s structure:

/mobile-esports-tournament-frontend
├── /public                 # Static files (e.g., index.html, images)
├── /src                    # Source code
│   ├── /components         # Reusable components (buttons, forms, etc.)
│   ├── /pages              # Pages for each route (Home, Profile, Tournament)
│   ├── /assets             # Static assets like images, logos
│   ├── /styles             # Tailwind CSS and custom styles
│   └── App.js              # Main React App component
├── /node_modules           # Installed npm packages
├── package.json            # npm configuration file
└── tailwind.config.js      # Tailwind CSS configuration file


Key Folders and Files
/src/components: Reusable UI components that make up the building blocks of your pages.
/src/pages: The actual page components (e.g., Home, Profile, Tournament).
/src/styles: Custom CSS files or Tailwind configuration to manage styles across the app.
tailwind.config.js: Tailwind CSS configuration file for customizing the design system.
Contributing
We welcome contributions! If you would like to contribute to the development of this project, follow these steps:

Fork the repository to your GitHub account.
Create a new branch for your feature or fix.
Commit your changes with clear messages.
Push your branch to your forked repository.
Open a pull request with a detailed description of your changes.
