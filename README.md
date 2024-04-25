# Ekart_Tracker
One stop for tracking, notification and product history analytics!
Amazon E-kart Tracker is a web application where you can add tracker for any product that is available on amazon and it will notify you when it notices a price drop in last 365 days, built using MongoDB, Express, React and Nodejs.

Features
Add products to track
Get notified on your mail when there is a price drop
Use line chart based analytics to visulaize price history
Tech
AMET uses the following tech:

React - HTML enhanced for web apps!
Puppeteer - Headless chrome nodejs API
[Express] - fast node.js network app framework [@tjholowaychuk]
[node.js] - evented I/O for the backend
Bootstrap - Bootstrap is a powerful, feature-packed frontend toolkit.
Setup
AMET requires Node.js v10+ to run.

Backend
Install the dependencies and devDependencies.

cd amazon-ekart-tracker
npm i
Create a .env file in root folder and add the following line with mongoDB URI to it.

MONGO_URI=<mongoDB connection URL>
To start the backend server open your terminal and type -

npm run start
Frontend
For frontend install the dependencies and start the server

cd frontend
npm i
npm run start
