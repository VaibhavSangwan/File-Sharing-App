# File Sharing App

A file sharing application built using Express.js, MongoDB, and JavaScript.

## Features

- Upload files to the server
- Generate unique download links for files
- Send files directly via email
- Authentication and authorization with JWT
- CORS setup for cross-origin resource sharing
- SMTP setup for sending emails using a third-party service
- Deployment to Heroku

## Prerequisites

- Node.js 
- MongoDB 
- NPM

## Deployment Link
 https://file-sharing-app-viaf.onrender.com/


## Description:

#1 Create server: Set up the server using Express.js, a web application framework for Node.js.

#2 MongoDB connection: Establish a connection to MongoDB, a NoSQL database, using the Mongoose module. Configure the connection by providing the MongoDB Atlas cluster link.

#3 Upload file endpoint: Create an endpoint in the server to handle file uploads. Implement Multer, a middleware for handling multipart/form-data, to handle file uploads efficiently. Define the destination folder for storing uploaded files and set a maximum file size.

#4 Download page: Set up a page where users can download files. This page can display a list of available files or provide a search functionality.

#5 Download link endpoint: Create an endpoint in the server to generate and provide download links for files stored in the database. When a user requests a download, the server generates a unique link that can be used to download the file.

#6 Send email endpoint: Implement an endpoint to send files to recipients via email. Use the Nodemailer module, which utilizes the SMTP (Simple Mail Transfer Protocol), to send emails. Configure the SMTP settings by providing the hostname, port, and authentication information (email user and password).

#7 SMTP setup: Set up the necessary SMTP configuration for sending emails using a third-party service like Sendinblue. This involves registering for an account, obtaining the required SMTP credentials, and configuring the transporter object in Nodemailer with the SMTP settings.

#8 CORS setup: Handle Cross-Origin Resource Sharing (CORS) to allow the frontend application hosted on a different domain to access the backend API. Configure the server to send appropriate Access-Control-Allow-Origin headers to specify which origins are allowed to access the API.

