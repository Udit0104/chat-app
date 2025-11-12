Chat App
A simple real-time chat application built with Node.js, Express, and Socket.io. This application allows multiple users to connect and broadcast messages to each other instantly.

Features
Real-time Messaging: Messages are sent and received instantly without needing to refresh the page.

Broadcast to All: Every message sent by a user is broadcast to all other connected users.

Simple UI: A clean and simple chat interface styled with CSS.

Technologies Used
Backend: Node.js, Express, Socket.io

Frontend: HTML, CSS, client-side JavaScript

Project Structure
chat-app/
├── public/
│   └── index.html    # The main client-side file
├── index.js          # The main server logic
└── package.json      # Project dependencies and metadata
Getting Started
Follow these instructions to get a copy of the project up and running on your local machine.

Prerequisites
nodejs and npm installed in your system

Installation
Navigate to the project directory:

Bash

cd chat-app
Install the required npm packages:

Bash

npm install
Running the Application
Start the server from the project's root directory:

Bash

node index.js
You should see a confirmation in your terminal that the server has started:

Server started at PORT: 9000
Open your web browser and navigate to http://localhost:9000.

Open multiple browser tabs or windows to the same address to simulate multiple users and start chatting.

Author
Udit Verma

License
This project is licensed under the ISC License.