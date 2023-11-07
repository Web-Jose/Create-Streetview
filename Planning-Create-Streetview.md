# Google Streetview API Web Application Plan

## Overview

This document describes the plan for the Google Streetview API Web Application. The application will be a web application that will allow users to sign in with their Google account and then upload a PhotoSphere image to Google Streetview based on the location of the image, location of the user, or a location specified by the user (longitude and latitude). The application will also allow users to view the images that they have uploaded to Google Streetview. Users will also be able to connect photospheres together to create a virtual tour. This is a project for Fresno State Student Housing and a learning experience, as many of the tools and technologies used in this project are new to the author.

## Goals

- The goals of this project are to create a web application that will allow users to upload photospheres to Google Streetview.
- The application will also allow users to connect photospheres together to create a virtual tour.
- The application will also allow users to view the photospheres that they have uploaded to Google Streetview.

## User Flow

- The user will be able to sign in with their Google account.
- The user will be able to upload a photosphere to Google Streetview.
- The user will be able to connect photospheres together to create a virtual tour.
- The user will be able to view the photospheres that they have uploaded to Google Streetview.

## Possible Technologies

### Front-End Development

1. **HTML/CSS/JavaScript:** Basic building blocks for web development to create the user interface.
2. **Google Maps JavaScript API:** Used to display the map and the photospheres.
3. **Street View Publish API:** Used to upload and edit metadata for photospheres to Google Streetview.

### Back-End Development

1. **Node.js:** Used to run the server and handle requests.
   - **Express.js:** Used to handle routing.
2. Authentication:
   - **Passport.js:** Used to authenticate users with their Google account.
   - **OAuth 2.0:** Used to authenticate users with their Google account.
3. **Database Options:**
   - **MySQL:** Used to store user information and photosphere metadata.
   - **PostgreSQL:** Used to store user information and photosphere metadata.
   - **MongoDB:** Used to store user information and photosphere metadata.
   - **Firebase Realtime Database:** Used to store user information and photosphere metadata.

### Google APIs:

1. **Google Maps JavaScript API:** Used to display the map and the photospheres.
2. **Street View Publish API:** Used to upload and edit metadata for photospheres to Google Streetview.
3. **Google OAuth2 API:** Used to authenticate users with their Google account.

### Hosting/ Deployment:

1. **Web Server:** Nginx or Apache for serving the web application.
2. **Cloud Hosting:** Amazon Web Services (AWS), Google Cloud Platform (GCP), or Microsoft Azure for hosting the web application.
3. **Domain Name:** Google Domains for the domain name.

### Development Tools:

1. **Git:** Used for version control.
2. **GitHub:** Used for hosting the repository.
3. **Visual Studio Code:** Used for writing code.
4. **Package Manager:** npm or yarn for installing dependencies.

### Testing:

1. **Manual Testing:** Used to test the application manually.
2. **Jest:** Used to test the application automatically.

### Additional Tools:
