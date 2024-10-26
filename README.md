A simple web application built with Node.js, Express, and EJS that fetches random secrets from an API and displays them on a web page.

Features

Fetches a random secret and user information from an external API
Displays the secret and user data in a styled format using EJS templates
Serves static files for styling

Technologies Used

Node.js: JavaScript runtime environment
Express: Web framework for Node.js
EJS: Templating engine for generating dynamic HTML
Axios: HTTP client for making requests to the API

Getting Started

Installation

Clone the repository:

git clone https://github.com/your-username/lisper.git
cd lisper
Install the dependencies:

npm install
Running the App
Start the server:

npm start
View in Browser: Open your browser and go to http://localhost:3000 to see the app in action.

Folder Structure

- public/
  └── styles/
      └── main.css     # Stylesheet for styling the page
- views/
  └── index.ejs        # EJS template for displaying secrets
- server.js            # Main server file with Express setup

API Used

This application utilizes the Secrets API to fetch random secrets. The response from this API includes:

secret: The random secret message
username: User who shared the secret





