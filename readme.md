# CodeCamp API

> Backend API for a CodeCamp Application which is a bootcamp directory website

- HTTP Essentials
- Postman Client
- RESTful APIs
- Express Framework
- Routing & Controller Methods
- MongoDB Atlas & Compass
- Mongoose ODM
- Advanced Query (Pagination, filter, etc)
- Models & Relationships
- Middleware (Express & Mongoose)
- MongoDB Geospatial Index / GeoJSON
- Geocoding
- Custom Error Handling
- User Roles & Permissions
- Aggregation
- Photo Upload
- Authentication With JWT & Cookies
- Emailing Password Reset Tokens
- Custom Database Seeder Using JSON Files
- Password & Token Hashing
- Security: NoSQL Injection, XSS, etc
- Creating Documentation
- Deployment With PM2, NGINX, SSL

## Usage

Rename "config/config.env.example" to "config/config.env" and update the values/settings to your own

## Install Dependencies

```
npm install
```

## Run App

```
# Run in development mode
npm run dev

# Run in Production mode
npm start
```

## Datebase Seeder

To seed the database with users, bootcamps, courses and reviews with data from the "\_data" folder, run

```
# Destroy all data
node seeder -d

# Import all data
node seeder -i
```

## Demo

The API is live [here](http://134.122.67.253/)

Extensive documentation with examples [here](https://documenter.getpostman.com/view/6291584/T17DiVFn?version=latest)

- Version: 1.0.0
- License: MIT
