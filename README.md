# Social Media Platform Backend

## Overview
This project is a backend application for a social media platform that combines features of YouTube and Twitter. It provides functionalities for users to upload, view, and interact with videos, as well as post and engage with tweets.
leave a star if you like.💖

## Key Features
- **User Authentication and Authorization:** Allows users to register, login, and manage their accounts securely. Authentication middleware ensures access control to specific routes based on user roles.
- **Video Management:** Enables users to upload videos with titles, descriptions, and thumbnails. Tracks views and likes for each video.
- **Commenting and Interaction:** Users can post comments on videos and tweets, as well as like them. Supports comment threads and replies for deeper interactions.
- **Tweeting and Timeline:** Allows users to post tweets with text content, which can be viewed, liked, and retweeted by others. A timeline feature displays tweets from followed users.
- **Playlist Creation and Management:** Users can create playlists to organize their favorite videos, with the ability to add or remove videos from playlists.
- **Cloudinary Integration:** Media files such as videos, thumbnails, avatars, and other assets are stored on Cloudinary. Integration includes upload and delete functions for managing media files.
- **Error Handling and Logging:** Implements error handling middleware to catch and handle errors throughout the application. Logging tracks application events and errors for debugging and monitoring purposes.

## Technologies Used
- **Backend Framework:** Node.js with Express.js
- **Database:** MongoDB with Mongoose
- **Cloud Storage:** Cloudinary
- **Authentication:** JSON Web Tokens (JWT)
- **Middleware:** Multer for file uploads, asyncHandler for error handling
- **Deployment:** Docker for containerization, potentially deployed on AWS, Heroku, or Azure cloud platforms.

## Future Enhancements
- Integration with frontend frameworks like React or Angular to create a complete application experience.
- Implementation of real-time features using WebSockets for live updates and notifications.
- Enhancement of security measures such as input validation, rate limiting, and CSRF protection.
- Addition of features like search functionality, user profiles, and trending topics.

## Installation
1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/AyushVerma-1307/Youtube-twitter-backend.git
    ```

2. Navigate to the project directory.
    ```bash
    cd Youtube-twitter-backend
    ```

3. Install dependencies.
    ```bash
    npm install
    ```

4. Set up environment variables.
    - Create a `.env` file in the root directory of the project.
    - Use the provided `.env.sample` file as a template and fill in the necessary values.
    - Save the file as `.env` in the root directory.

5. Run the application.
    ```bash
    npm run dev
    ```

6. The application should now be running locally. You can access it at `http://localhost:8000`.

## Postman API Documentation
Explore the available API endpoints and test them using Postman. Import the provided collection and environment files into your Postman workspace to get started.

### Importing Postman Collection
- use `youtube clone.postman_collection` to import the Postman Collection.

Once imported, you can start testing the APIs.

## Screenshots
### Register Api Response Screenshot
![Register Api Response Screenshot](https://github.com/AyushVerma-1307/Youtube-twitter-backend/blob/main/public/test%20images/register%20api%20response.PNG?raw=true)

### Login Api Response Screenshot
![Login Api Response Screenshot](https://github.com/AyushVerma-1307/Youtube-twitter-backend/blob/main/public/test%20images/login%20api%20response.PNG?raw=true)

### Register Controller Screenshot
![Register Screenshot](https://github.com/AyushVerma-1307/Youtube-twitter-backend/blob/main/public/test%20images/controller.PNG?raw=true)


