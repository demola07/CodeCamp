# CodeCamp API

> Backend API for a CodeCamp Application which is a bootcamp directory website

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

To seed the database with users, bootcamps, courses and reviews with data from the "_data" folder, run

```
# Destroy all data
node seeder -d

# Import all data
node seeder -i
```

- Version: 1.0.0
- License: MIT


