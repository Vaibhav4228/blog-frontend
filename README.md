# ZuAi Blog Application

Welcome to ZuAi, a modern blog application where you can create, read, update, and delete blog posts. This project includes a variety of features such as user profiles, search functionality, comments, image uploads, and more.

## Live Demo

Check out the live version of the application [here](https://zuai-lime.vercel.app/).

## Backend Repository

The backend code for this application is available on GitHub: [blog-server](https://github.com/Vaibhav4228/blog-server).

## Deployment

- **Frontend**: Deployed on Vercel. [Live Frontend](https://zuai-lime.vercel.app/)
- **Backend**: Deployed on Render. [Live Backend](https://blog-server-jqci.onrender.com)

## Features

- **Search Functionality**: Allows users to search for blog posts based on keywords.
- **Comment Functionality**: Users can add, edit, and delete comments on blog posts.
- **Post Management**: Create new blog posts, upload images using Multer, edit existing posts, and delete posts.
- **Profile Page**: Users can update their profile information.
- **My Blogs Page**: View a list of all your blog posts.

## Running Locally

To run the application locally, make the following changes:

1. **Backend**: Replace the Render URL `https://blog-server-jqci.onrender.com` with `http://localhost:5000` in the `index.js` file of the backend for CORS configuration.
2. **Frontend**: Replace the Vercel URL `https://zuai-lime.vercel.app/` with `http://localhost:5173/` in the `index.js` file of the frontend for CORS configuration.

### Backend Setup

Clone the backend repository:
```bash
git clone https://github.com/Vaibhav4228/blog-server
cd blog-server
npm install
npm start


````
### .env setup
```bash
Backend:
  MONGODB_URI= your mongodb url
SECRET = Make your own secrete key

Frontend:
  VITE_URL="https://blog-server-jqci.onrender.com"
  VITE_IF="https://blog-server-jqci.onrender.com/images/"
````

## Features

- **Search Functionality**: Allows users to search for blog posts based on keywords.
- **Comment Functionality**: Users can add, edit, and delete comments on blog posts.
- **Post Management**: Create new blog posts, upload images using Multer, edit existing posts, and delete posts.
- **Profile Page**: Users can update their profile information.
- **My Blogs Page**: View a list of all your blog posts.

## Running Locally

To run the application locally, make the following changes:

1. **Backend**: Replace the Render URL `https://blog-server-jqci.onrender.com` with `http://localhost:5000` in the `index.js` file of the backend for CORS configuration.
2. **Frontend**: Replace the Vercel URL `https://zuai-lime.vercel.app/` with `http://localhost:5173/` in the in all places for locally running.
