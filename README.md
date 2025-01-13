# StudyNotion Edtech Project

```markdown
# MERN Stack Project

## Overview

 StudyNotion is a fully functional ed-tech platform that enables users to create, consume, 
and rate educational content. The platform is built using the MERN stack, which includes 
ReactJS, NodeJS, MongoDB, and ExpressJS.

## Technologies Used

### Frontend

- React.js: JavaScript library for building user interfaces
- Redux: State management for React applications
- Tailwind CSS: Utility-first CSS framework for styling

### Backend

- Node.js: JavaScript runtime environment
- Express.js: Web framework for Node.js
- MongoDB: NoSQL database
- Mongoose: MongoDB object modeling tool

### Additional Tools

- Concurrently: Runs multiple commands concurrently for server and client


## Getting Started

### Prerequisites

- Node.js (download from [Node.js website](https://nodejs.org/))
- MongoDB (set up local or cloud instance)
```
### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Devgupta851900/StudyNotion.git
   cd <project-folder>
   ```

2. **Install server and client dependencies:**

   ```bash
   npm install
   cd ../server
   npm install
    cd ..
   ```

3. **Set up environment variables:**

   Create a `.env` file in the Server directory and add your configuration:

   ```env
   PORT = <your_port_number>
   MONGODB_URL = <your_mongobd_url>
   JWT_SECRET = <your_jwt_secret>
   CLOUDINARY_NAME = <your_cloudinary_name>
   CLOUDINARY_API_KEY = <your_cloudinary_api_key>
   CLOUDINARY_API_SECRET = <your_cloudinary_api_secret>
   CLOUDINARY_FOLDER = <your_cloudinary_folder_name>
   MAIL_HOST = <your_mail_host>
   MAIL_USER = <your_mail_username>
   MAIL_PASS = <your_mail_password>
   RAZORPAY_KEY = <your_razorpay_key>
   RAZORPAY_SECRET = <your_razorpay_secret>

   ```

### Running the Application

1. **Start the development server:**

   ```bash
  
   npm run dev
   ```

   This starts both the server and client.

2. **Access the application:**

   Open `http://localhost:3000` in your web browser.
