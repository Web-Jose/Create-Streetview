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

1. **API Testing:** Postman for testing the API.
2. **Analytics:** Google Analytics for tracking user activity.

## Structure

### Navigation Structure

- **Header:**

  - **Logo:** The logo will be a link to the home page.
  - **Home:** The home link will be a link to the home page.
  - **Upload Photosphere:** The upload link will be a link to the upload page.
  - **Virtual Tour:** The virtual tour link will be a link to the virtual tour page.
  - **My Photospheres:** The my photospheres link will be a link to the my photospheres page.
  - **Sign In:** The sign in link will be a link to the sign in page.
  - **Sign Out:** The sign out link will be a link to the sign out page.

- **Footer:**

  - **Project Name and small description:** The project name and small description will be displayed at the top of the footer.
  - **Contact Us:** The contact us link will be a link to the contact us page.
  - **About Us:** The about us link will be a link to the about us page.
  - **Privacy Policy:** The privacy policy link will be a link to the privacy policy page.
  - **Terms of Service:** The terms of service link will be a link to the terms of service page.
  - **Report a Bug:** The report a bug link will be a link to the report a bug page.
  - **Social Media Links:** The social media links will be links to the social media pages.

### Pages and Components

- **Home Page:**

  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **Welcome Banner:** Briefly describes the application.
  - **Feature Highlights:** Overview of key features like uploading photospheres, creating virtual tours, and viewing uploaded content.
  - **Explore Photospheres:** Displays a gallery of photospheres that users have uploaded.
  - **Featured Virtual Tours:** Displays a gallery of virtual tours that users have created.
  - **Call to Action:** Sign-in button for new users and quick access for returning users.
  - **News and Updates:** Displays news and updates about the application.

- **Sign-in/ Registration Page:**

  - **Google OAuth Sign-in:** Allows users to sign-in with their Google account.
  - **User Onboarding:** Instructions for new users on how to use the application.

- **Upload Photosphere Page:**

  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **Upload Interface:** Drag and drop or file selection options.
  - **Location Selection:** Select location from map or enter longitude and latitude.
  - **Metadata Editor:** Enter metadata for the photosphere.

- **Virtual Tour Creation Page:**

  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **Tour Builder:** Select photospheres to connect together to create a virtual tour.
  - **Tour Preview:** Preview the virtual tour.
  - **Save/ Share:** Save the virtual tour or share it with others.

- **My Photospheres Page:**

  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **Gallery:** Displays the photospheres that the user has uploaded.
  - **Filter/ Sort:** Filter and sort the photospheres.
  - **Edit/ Delete:** Edit metadata or delete photospheres.

- **Individual Photosphere View:**

  - **Interactive Viewer:** Display the selected photosphere with pan and zoom functionalities.
  - **Metadata Display:** Show the metadata associated with the photosphere.
  - **Navigation Links:** To the next/previous photosphere or back to the gallery.

- **Contact Us Page:**

  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **Contact Form:** Allows users to send a message to the developers.

- **About Us Page:**

  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **About Us:** Information about the developers and the project.

- **Privacy Policy Page:**

  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **Privacy Policy:** Information about the privacy policy.

- **Terms of Service Page:**

  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **Terms of Service:** Information about the terms of service.

- **Report a Bug Page:**
  - **Header:** The header will be displayed at the top of the page.
  - **Footer:** The footer will be displayed at the bottom of the page.
  - **Bug Report Form:** Allows users to report a bug.
