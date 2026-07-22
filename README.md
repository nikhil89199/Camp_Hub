# Camp_Hub
CampHub is a full-stack web application that helps users discover, share, and review campgrounds from around the world. It features user authentication, image uploads and a review system for a seamless camping experience.

Features
User Registration and Login
Secure Authentication using Passport.js
Create, Edit, and Delete Campgrounds
Upload Campground Images
Add and Delete Reviews
Authorization and Ownership Checks
Flash Messages for User Feedback
Server-Side Validation using Joi
MongoDB Database Integration
Responsive UI using Bootstrap
Tech Stack
Backend
Node.js
Express.js
MongoDB
Mongoose
Authentication
Passport.js
Passport Local
Passport Local Mongoose
Validation
Joi
File Uploads
Multer
Cloudinary
Frontend
EJS
Bootstrap
Project Structure
mapcamp/
│
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── utils/
├── middleware.js
├── schemas.js
├── cloudinary/
├── app.js
├── package.json
└── README.md
Installation
1. Install Dependencies
npm install
2. Create Environment Variables
Create a .env file in the root directory:

DB_URL=mongodb://localhost:27017/mapcamp
SECRET=yourSecretKey

MAPBOX_TOKEN=your_mapbox_token

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_KEY=your_cloudinary_key
CLOUDINARY_SECRET=your_cloudinary_secret
3. Seed Database (Optional)
node seeds/index.js
4. Run Application
node app.js
or

nodemon app.js
Default Routes
Authentication
Method	Route	Description
GET	/register	Registration Form
POST	/register	Register User
GET	/login	Login Form
POST	/login	Login User
GET	/logout	Logout User
Campgrounds
Method	Route	Description
GET	/campgrounds	View All Campgrounds
GET	/campgrounds/new	New Campground Form
POST	/campgrounds	Create Campground
GET	/campgrounds/:id	Show Campground
GET	/campgrounds/:id/edit	Edit Campground
PUT	/campgrounds/:id	Update Campground
DELETE	/campgrounds/:id	Delete Campground
Reviews
Method	Route	Description
POST	/campgrounds/:id/reviews	Create Review
DELETE	/campgrounds/:id/reviews/:reviewId	Delete Review
Security Features
Password Hashing
Authentication Middleware
Authorization Checks
Input Validation
Session Management
Flash Messages
Error Handling Middleware
Future Improvements
Search and Filter Campgrounds
User Profiles
Favorite Campgrounds
Rating System
Admin Dashboard
REST API Support
Responsive Mobile UI Enhancements
Author
Developed as a full-stack web development project using the MERN ecosystem principles with Express and MongoDB.

License
This project is intended for educational purposes.
