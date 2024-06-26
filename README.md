# Cloudinary CRUD Operations MERN Stack Application

## Project Description

The Cloudinary CRUD operations MERN stack application is a web project designed for efficient image management. It allows users to perform CRUD operations (Create, Read, Update, Delete) on images using the MERN (MongoDB, Express.js, React.js, Node.js) stack. The application leverages Cloudinary, a cloud-based image management platform, for secure and streamlined image handling.

### Key Features

- CRUD operations for images
- MERN stack development
- Cloudinary integration for image management
- User-friendly interface built with React.js
- Efficient image storage and retrieval with MongoDB
- Streamlined image handling for web applications

### Tech Stack Used

- MongoDB
- Express.js
- React.js
- Node.js
- Cloudinary

## Challenges Faced

During the development of the Cloudinary CRUD operations MERN stack application, a significant challenge was seamlessly integrating with Cloudinary for image management. This involved ensuring secure image uploads, tracking changes made to images, and efficiently managing resources.

Securely handling image uploads and accommodating various image formats and sizes added complexity. Additionally, accurately reflecting modifications or deletions to images in the Cloudinary database required meticulous attention to detail.

The challenge extended beyond technical aspects to considerations for user experience. Striking the right balance between functionality, security, and user-friendliness was crucial in overcoming this challenge and delivering a reliable image management system.


### User

- **POST** `/user`: Create a new user
- **GET** `/user`: Get all users
- **GET** `/user/{id}`: Get a user by ID
- **PUT** `/user/{id}`: Update a user by ID
- **DELETE** `/user/{id}`: Delete a user by ID

## Setup Guide

Follow these steps to set up and run the Cloudinary CRUD operations MERN stack application locally:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/akil555/profile_crud_mern_with_cloudinary.git
   cd Cloudinary-CRUD-Operations

   ```

2. **Installing Dependencies:**
   ```bash
    cd client
    npm install
    cd ../server
    npm install
   ```
3. **Setting Up `.env` Credentials**

   To enable seamless image management functionalities, you'll need Cloudinary API credentials, and for saving those images location and other data you will need mongodb url.

   Follow these steps:

   1. Obtain Cloudinary API & MongoDB credentials.
   2. Create a `.env` file in the `server` directory.
   3. Add your credentials to the `.env` file:

   ```env
   CLOUDINARY_CLOUD_NAME=your-cloud-name
   CLOUDINARY_API_KEY=your-api-key
   CLOUDINARY_API_SECRET=your-api-secret
   MONGO_URI=your-mongodb-uri
   ```

Create a `.env` file in your client directory and provide your live server URL

    REACT_APP_SERVER_URL= your-server-url

4. **Starting the Server**

   Start the server by running the following command in the server directory:

   ```
   cd server
   npm start
   ```

5. **Starting the Client**

   Begin the client application with the following command in the client directory:

   ```
   cd client
   npm start
   ```

6. **Accessing the Application**

   You're all set! Open your browser and go to http://localhost:3000 to access the Cloudinary CRUD operations application.

## Contribute and Support ❤️

If you find this project useful and would like to contribute or show your support, we welcome your involvement. Feel free to submit pull requests, report issues, or share your feedback. Your contributions make this project even better!

Also, don't forget to give a star ⭐ to this repo
