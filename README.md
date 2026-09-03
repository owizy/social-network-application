# Social Media Application

A full-stack social media platform built with the **MERN stack** that allows users to connect, share content, interact with posts, and manage their profiles. The application is fully responsive and includes powerful user and administrator features.

## ✨ Features

### 👤 User Features

* 🔐 User registration and login
* 🖼️ Upload images from a device or camera
* 📝 Create and edit posts
* ❤️ Like, comment, and share posts
* 💬 Reply to comments
* ❤️ Like comments
* 🖼️ Create posts with captions and images
* 🔍 Search users by username
* 👥 Follow and unfollow users
* 🤝 User suggestions
* 🔖 Save posts to a personal collection
* 📚 View saved posts
* 🗑️ Delete posts and comments
* 🚨 Report posts as spam
* 🔗 Copy and share post links
* 🔔 Notifications system
* 🧭 Explore page for discovering posts from other users
* 👤 User profile pages
* ✏️ Edit profile information
* 🌙 Dark mode
* 📄 Pagination across pages
* 🔔 Clear notifications
* 🔒 Secure password storage with encryption and salting

### 🛡️ Admin Features

* 📊 Admin dashboard with platform statistics
* 👥 View total registered users
* 📝 View total posts
* 🚨 Monitor reported posts
* 👑 Create and assign administrator accounts
* 🔎 Review posts reported by multiple users
* 🗑️ Delete reported posts when necessary

## 🛠️ Tech Stack

### Frontend

* React
* Redux
* JavaScript
* HTML5
* CSS3

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* MongoDB Atlas

### Cloud Services

* Cloudinary for image uploads and management

## 📋 Prerequisites

Before running the application, make sure you have the following installed or configured:

* Node.js
* npm
* MongoDB or MongoDB Atlas
* Cloudinary account

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/owizy/social-media-application.git
cd social-media-application
```

### 2. Configure MongoDB

Make sure MongoDB is running locally or use MongoDB Atlas.

Create a `.env` file in the project root:

```env
MONGODB_URI=your_mongodb_connection_string
```

Replace the placeholder with your MongoDB connection string.

### 3. Configure Cloudinary

Configure your Cloudinary credentials in the image upload configuration.

For production applications, it is recommended to store Cloudinary credentials in environment variables rather than directly in source files.

### 4. Install Backend Dependencies

From the project root:

```bash
npm install
```

### 5. Start the Backend

```bash
node server
```

### 6. Install Frontend Dependencies

Navigate to the client directory:

```bash
cd client
npm install
```

### 7. Start the Frontend

```bash
npm start
```

The application will be available at:

```text
http://localhost:3000
```

## 📱 Application Highlights

The platform provides a complete social networking experience where users can:

* Create and share posts
* Upload and manage images
* Like and comment on content
* Reply to comments
* Follow other users
* Discover suggested users
* Search for users
* Save posts
* Explore content from the community
* Receive notifications
* Manage their profiles
* Report inappropriate content
* Switch between light and dark modes

Administrators have additional tools for managing users, posts, and reported content.

## 📸 Screenshots

### Login Page

[View Login Page](https://user-images.githubusercontent.com/72184791/114161303-877f6b80-9945-11eb-89a7-f05b560bb5e4.JPG)

![Login Page](https://user-images.githubusercontent.com/72184791/114161303-877f6b80-9945-11eb-89a7-f05b560bb5e4.JPG)

### Admin Panel

[View Admin Panel](https://user-images.githubusercontent.com/72184791/114161299-877f6b80-9945-11eb-9791-cab82f92bd7e.JPG)

![Admin Panel](https://user-images.githubusercontent.com/72184791/114161299-877f6b80-9945-11eb-9791-cab82f92bd7e.JPG)

### Profile Page

[View Profile Page](https://user-images.githubusercontent.com/72184791/114161324-8b12f280-9945-11eb-96a2-0707ee234c8a.JPG)

![Profile Page](https://user-images.githubusercontent.com/72184791/114161324-8b12f280-9945-11eb-96a2-0707ee234c8a.JPG)

### Home Page

[View Home Page](https://user-images.githubusercontent.com/72184791/114161305-88180200-9945-11eb-9856-a4b33b8e9def.JPG)

![Home Page](https://user-images.githubusercontent.com/72184791/114161305-88180200-9945-11eb-9856-a4b33b8e9def.JPG)

### Create New Post

[View New Post](https://user-images.githubusercontent.com/72184791/114161309-89492f00-9945-11eb-888f-3ff263cfb909.JPG)

![New Post](https://user-images.githubusercontent.com/72184791/114161309-89492f00-9945-11eb-888f-3ff263cfb909.JPG)

### Dark Mode

[View Dark Mode](https://user-images.githubusercontent.com/72184791/114161287-851d1180-9945-11eb-8a0e-1a4c56132de0.JPG)

![Dark Mode](https://user-images.githubusercontent.com/72184791/114161287-851d1180-9945-11eb-8a0e-1a4c56132de0.JPG)

### Search Users

[View Search Users](https://user-images.githubusercontent.com/72184791/114161296-86e6d500-9945-11eb-85cb-eb7c84d4abda.JPG)

![Search Users](https://user-images.githubusercontent.com/72184791/114161296-86e6d500-9945-11eb-85cb-eb7c84d4abda.JPG)

### Post Menu

[View Post Menu](https://user-images.githubusercontent.com/72184791/114161315-89e1c580-9945-11eb-8f9f-4156d1184567.JPG)

![Post Menu](https://user-images.githubusercontent.com/72184791/114161315-89e1c580-9945-11eb-8f9f-4156d1184567.JPG)

### Explore Page

[View Explore Page](https://user-images.githubusercontent.com/72184791/114161321-8a7a5c00-9945-11eb-8c67-bf42a8f30fcd.JPG)

![Explore Page](https://user-images.githubusercontent.com/72184791/114161321-8a7a5c00-9945-11eb-8c67-bf42a8f30fcd.JPG)

## 📂 Project Structure

```text
social-media-application/
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
├── server/
├── .env
├── package.json
└── README.md
```

> The exact project structure may vary depending on your implementation.

## 🤝 Contributing

Contributions are welcome and appreciated.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Make your changes
4. Commit your changes

```bash
git add .
git commit -m "Add new feature"
```

5. Push your branch

```bash
git push origin feature/new-feature
```

6. Open a Pull Request

## 📄 License

This project is available under the **MIT License**.


