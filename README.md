# My MERN Stack Blog Application

Welcome to my blog application! This is a full-featured blogging platform built with the MERN stack (MongoDB, Express, React, Node.js). The application provides a modern, responsive interface for creating and managing blog content with robust user management features.Dedicating this project to my lil brother Rishabh.

#Demo:https://blogify-mern-app.onrender.com/

## Technologies Used

- **Frontend**: React.js, Redux Toolkit, TailwindCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT, Google OAuth
- **Image Storage**: Firebase Storage

This README will guide you through the key features and functionalities of Blogify:

## Project Structure

* `client`: Contains the React frontend codebase for the application.
* `server`: Houses the Node.js backend code responsible for server-side logic and API endpoints.


## Navigating Blogify

## Features

1. **User Authentication**
   - Email/Password registration and login
   - Google OAuth integration
   - JWT-based authentication
   - Password reset functionality

2. **Blog Management**
   - Create, read, update, and delete blog posts
   - Rich text editor for post content
   - Image upload support
   - Post categories and tags
   
3. **Admin Dashboard**
   - User management
   - Content moderation
   - Analytics dashboard
   - Comment management

4. **User Features**
   - Profile customization
   - Comment on posts
   - Like and share posts
   - Follow other users

5. **UI/UX**
   - Responsive design
   - Dark/Light mode
   - Infinite scroll
   - Search functionality

This section is accessible only to authenticated users.

Here, users can create new blog posts by providing a title, image, content, and potentially adding categories or tags.

### 6. **Update Post:**

![update post](https://github.com/RishabhJain2404/blogify-mern-app/assets/127675963/6058276a-e503-4a31-b09b-896429592732)

This section is accessible only to authenticated users and only for posts the user created.

Users can edit existing blog posts by modifying the title, image, content, or associated categories/tags.

### 7. **Search:**

![search](https://github.com/RishabhJain2404/blogify-mern-app/assets/127675963/cdffcf1b-b5e2-4035-b0ad-ef8e12cf3f4f)

The search functionality allows users to find specific blog posts based on keywords or criteria. You can highlight the advanced search features like filtering and sorting capabilities here.

### 8. **Post Details:**

![post details](https://github.com/RishabhJain2404/blogify-mern-app/assets/127675963/e7807289-656c-4726-ad49-199968a3d45f)

This page displays the details of an individual blog post, including the title, image, content, date, mins of read and potentially comments and likes from other users.


## Getting Started

1. **Clone the repository:**

   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/blogify.git


2. **Install dependencies:**

   ```bash
   cd blogify
   npm install

3. **Configure environment variables:**

Create a `.env` file in the project root directory and add the following variables (replace with your actual values):

  
    MONGODB_URI=mongodb://localhost:27017/<your-database-name>
    JWT_SECRET=<your-jwt-secret>
    GOOGLE_CLIENT_ID=<your-google-client-id>
    GOOGLE_CLIENT_SECRET=<your-google-client-secret>

4. **Run the application:**

    ```bash
    npm start

This will start the development server on `http://localhost:3000` by default.


## Deployment


You can deploy the application to a hosting platform of your choice. Refer to the platform's documentation for specific deployment instructions.
