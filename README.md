# Node.js Cloudinary Integration App

A Node.js application integrated with Cloudinary, allowing users to upload images and videos, resize images, and more. The app provides different API routes for various tasks and uses Nodemailer to send emails when data is created in the database.

**Features**
  Image and Video Upload: Upload images and videos to Cloudinary.
  Image Resizing: Reduce the size of uploaded images.
  API Routes: Separate API routes for different tasks.
  Email Notifications: Send emails using Nodemailer when data is created in the database.

**Installation**
  Clone the repository from GitHub.
  Install the necessary dependencies using npm.
  Set up the required environment variables in a .env file.
  Start the application using npm.

**Usage**
  The application provides endpoints for various tasks, including uploading images and videos and resizing images. Users can interact with these endpoints using HTTP requests.

**API Documentation**

**Upload an Image**
  **Endpoint**: POST /api/upload/image
  **Description**: Uploads an image to Cloudinary.
  
**Upload a Video**
  **Endpoint**: POST /api/upload/video
  **Description**: Uploads a video to Cloudinary.

**Resize an Image**
  **Endpoint**: POST /api/upload/resize
  **Description**: Uploads and resizes an image.

**Configuration**
  Ensure the .env file contains the necessary environment variables, such as Cloudinary credentials and email service details for Nodemailer.

**Contributing**
  Contributions are welcome! Please fork the repository and submit a pull request with your changes.
