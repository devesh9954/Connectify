# Connectify

Connectify is a full-stack social media application designed for seamless user interactions through posts, messaging, and notifications. It offers a dynamic user experience with real-time features and a robust backend.

## Features

- **User Authentication & Authorization**: Secure signup, login, and logout functionalities using JWT tokens.
- **Post Management**: Create, like, and reply to posts. Supports user feeds and image uploads via Cloudinary.
- **Real-Time Messaging**: One-on-one messaging with live status indicators.
- **User Profiles & Social Features**: Follow/unfollow users, view profiles, and see suggested users.
- **Frontend**: Responsive and dynamic UI built with React.
- **Backend**: Handles API requests, data processing, and business logic.
- **Image Storage**: Efficient management and retrieval of images using Cloudinary.
- **Real-Time Features**: Real-time messaging and online status indicators via Socket.io. Server activity is maintained using a cron job.

## Technologies Used

### Backend
- **Node.js**: JavaScript runtime environment used for building the backend.
- **Express**: Web framework for Node.js, handling API requests and routing.
- **MongoDB**: NoSQL database for storing user data, posts, messages, and more.
- **JWT**: JSON Web Tokens for secure user authentication and authorization.

### Frontend
- **React**: JavaScript library for building the user interface.
- **HTML5 & CSS3**: Markup and styling for building the UI components.

### Real-Time Communication
- **Socket.io**: Enables real-time, bidirectional communication for messaging and online status updates.

### Image Storage
- **Cloudinary**: Manages and stores images for posts and user profiles.

### Miscellaneous
- **Cron**: Scheduled tasks to keep the server active during low traffic periods.

## Getting Started

To run this project locally, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/connectify.git
    cd connectify
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Setup Environment Variables**:
    - Create a `.env` file in the root directory and add the following:
        ```plaintext
        MONGO_URI=your_mongo_uri
        JWT_SECRET=your_jwt_secret
        CLOUDINARY_CLOUD_NAME=your_cloud_name
        CLOUDINARY_API_KEY=your_api_key
        CLOUDINARY_API_SECRET=your_api_secret
        ```

4. **Run the Application**:
    ```bash
    npm start
    ```

## Contributing

Feel free to fork this repository and contribute via pull requests. For major changes, please open an issue first to discuss what you would like to change.


