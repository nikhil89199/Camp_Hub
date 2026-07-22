#  CampHub

CampHub is a full-stack web application that enables users to explore, create, and manage campgrounds. Users can register, log in, add new campgrounds, upload images, leave reviews, and discover camping destinations through an interactive and user-friendly interface.

---

## Features

-  User Registration & Login
-  Secure Authentication with Passport.js
-  Create, View, Edit, and Delete Campgrounds
-  Add and Manage Reviews
-  Upload Campground Images
-  Location-based Campground Listings
-  Responsive User Interface
-  Server-side Validation using Joi
-  Authorization for Campground Owners
-  Flash Messages for Notifications
-  Custom Error Handling

---

##  Tech Stack

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- EJS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- Passport.js
- Passport Local Mongoose

### Template Engine
- EJS
- EJS-Mate

### Validation
- Joi

### File Upload
- Multer

---

##  Project Structure

```
CampHub/
│
├── models/
├── routes/
├── controllers/
├── middleware/
├── views/
│   ├── layouts/
│   ├── campgrounds/
│   ├── reviews/
│   └── users/
├── public/
│   ├── css/
│   ├── js/
│   └── images/
├── app.js
├── package.json
└── README.md
```

---

##  Dependencies

| Package | Purpose |
|----------|---------|
| express | Web framework for Node.js |
| passport | User authentication |
| passport-local-mongoose | Simplifies user authentication with MongoDB |
| joi | Request validation |
| multer | Image/file upload |
| connect-flash | Flash notification messages |
| ejs-mate | Layout support for EJS |
| colors | Colored console output |
| figlet | Stylish ASCII banners in terminal |

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/CampHub.git
```

### Navigate to the project

```bash
cd CampHub
```

### Install dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory and add the required environment variables.

Example:

```env
DB_URL=your_mongodb_connection_string
SECRET=your_session_secret
```

---

##  Run the Application

Using Node.js:

```bash
npm start
```

Or with Nodemon:

```bash
nodemon app.js
```

Open your browser and visit:

```
http://localhost:3000
```

---

## 📸 Application Modules

### Authentication
- Register User
- Login User
- Logout User

### Campgrounds
- View All Campgrounds
- View Campground Details
- Add Campground
- Edit Campground
- Delete Campground

### Reviews
- Add Reviews
- Edit Reviews
- Delete Reviews

### Validation
- Server-side Form Validation
- Custom Error Messages

---

##  Security Features

- Password Hashing using Passport Local Mongoose
- User Authentication
- Route Protection
- Input Validation using Joi
- Flash Messages for User Feedback

---

##  Future Enhancements

- Interactive Maps
- Cloud Image Storage
- Favorite Campgrounds
- Search & Filter
- User Profiles
- Online Booking
- Payment Gateway
- Admin Dashboard

---

##  Author

**Nikhil T**




