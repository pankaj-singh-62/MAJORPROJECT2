<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">StaySmart</h1>
</p>
<p align="center">
    <em>Make your travell easy with StaySmart</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/Shashi-Srivastav/Namaste-Yatra?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/Shashi-Srivastav/Namaste-Yatra?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Shashi-Srivastav/Namaste-Yatra?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Shashi-Srivastav/Namaste-Yatra?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
	<img src="https://img.shields.io/badge/Passport-34E27A.svg?style=flat&logo=Passport&logoColor=white" alt="Passport">
	<img src="https://img.shields.io/badge/Express-000000.svg?style=flat&logo=Express&logoColor=white" alt="Express">
	<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
</p>
<hr>

<div>


# StaySmart File Structure

```plaintext
StaySmart/
├── .git/                         # Git configuration and metadata
│   ├── ...
├── .github/                      # GitHub-specific files
│   ├── workflows/                # GitHub Actions workflows
│   │   ├── ...
│   └── ...
├── controllers/                  # Controllers for handling requests
│   ├── ...
│   └── ...
├── models/                       # Data models or schemas
│   ├── User.js
│   ├── Listing.js
│   └── ...
├── public/                       # Public static files
│   ├── assets/                   # Static assets (images, fonts, etc.)
│   │   ├── logo.png
│   │   └── ...
│   ├── index.html                # Main HTML file
│   ├── favicon.ico               # Favicon
│   └── manifest.json             # Web app manifest
├── routes/                       # Route definitions
│   ├── index.js
│   └── ...
├── utils/                        # Utility functions and helpers
│   ├── formatDate.js
│   └── ...
├── views/                        # Views for rendering templates
│   ├── Home.js
│   ├── Listings.js
│   └── ...
├── .env                          # Environment variables
├── .gitignore                    # Git ignore file
├── README.md                     # Project documentation
├── SECURITY.md                   # Security-related documentation
├── app.js                        # Main application entry point
├── cloudConfig.js                # Configuration for cloud services
├── middleware.js                 # Middleware for request processing
├── package-lock.json             # NPM lock file
├── package.json                  # NPM package configuration
├── schema.js                     # Database schema definitions
└── vercel.json                   # Vercel deployment configuration
```

## Technologies Used

 - [JavaScript (Node.js)]()
 - [Express.js]()
 - [MongoDB]()
 - [Mongoose]()
 - [Bootstrap]()
 - [Passport.js]()
 - [Mapbox]()
 - [Cloudinary]()
 - [EJS]()
 - [Joi]()

## Features
# StaySmart: Key Features

## User Authentication and Security:
- **Passport Integration:** Secure sign-up and login.
- **Express Sessions:** Persistent user sessions in MongoDB Atlas.

## Dynamic Listing Creation:
- **Cloudinary Image Uploads:** Supports PNG, JPG, JPEG up to 500KB.
- **Joi Validation:** Ensures data integrity during listing creation.

## Interactive Maps and Geolocation:
- **Mapbox Integration:** Interactive maps with zoom and full-screen features.
- **Geocoding:** Converts text locations to coordinates.

## Comprehensive Listing Details:
- **Detailed Information:** Displays name, location, price, and user reviews.
- **Map Integration:** Embedded Mapbox maps for each listing.

## User Reviews and Community Interaction:
- **Review System:** Users can leave detailed reviews.
- **Map-Enhanced Reviews:** Reviews include geolocation data.

## Responsive Design:
- **Bootstrap Framework:** Consistent UI across desktops, tablets, and mobiles.

## Scalable Data Management:
- **Mongoose and MongoDB:** Flexible and scalable data storage.
- **MongoDB Atlas:** Reliable cloud-based storage.

## Robust Back-End Architecture:
- **Express.js Framework:** Efficient server-side structure.
- **MVC Pattern:** Organized and scalable codebase.

## Enhanced User Experience:
- **Interactive Elements:** Zoomable and full-screen maps.
- **Performance Optimization:** Quick load times with Cloudinary.

## Comprehensive Schema Validation:
- **Joi Validation:** Maintains data consistency and integrity.

## Secure and Efficient Middleware:
- **Express Middleware:** Manages request processing and authentication.

## Scalable Cloud Integration:
- **Cloudinary for Image Management:** Efficient media handling.
- **MongoDB Atlas for Data Storage:** Reliable and scalable solutions.
## Environment Variables

```javascript
CLOUD_NAME=
CLOUD_API_KEY=
CLOUD_API_SECRET=
MAP_TOKEN=
ATLASDB_URL=
SECRET=dtrvstyjtvhdtcd
```

## Feedback

If you have any feedback, please reach out to us at pankajsingh22065@gmail.com
