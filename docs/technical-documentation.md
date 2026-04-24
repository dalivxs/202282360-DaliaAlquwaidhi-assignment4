# Technical Documentation – Assignment 4

## Overview
This project is the final version of a responsive personal portfolio web application developed using HTML, CSS, and JavaScript. It combines all features from previous assignments into a complete, polished, and fully deployed application. The project demonstrates API integration, complex logic, state management, and a professional user experience.

## Technologies Used
- HTML5 – Structure and semantic layout
- CSS3 – Styling, layout, responsive design, and transitions
- JavaScript – Interactivity, API integration, logic handling, and state management
- GitHub API – Fetching and displaying real-time repository data
- GitHub Pages – Deployment and hosting of the live website

## Website Structure

### index.html
Contains the main structure of the website:
- Header with navigation
- Hero section with dynamic greeting
- Visitor name section (state management feature)
- About section
- Personal Highlights section (represents user personality and interests)
- Projects section (with search, filter, and sorting features)
- GitHub repositories section (API integration)
- Contact form
- Footer

### css/styles.css
Handles:
- Layout and spacing
- Responsive design for different screen sizes
- Dark/light theme styling
- Hover effects and transitions
- Styling for cards, buttons, and sections

### js/script.js
Implements:
- Dynamic greeting based on time of day
- Dark/light theme toggle with localStorage
- Visitor name storage and display using localStorage
- Contact form validation with multiple conditions
- Search functionality for projects
- Sorting projects (by name and year)
- Filtering projects by level (beginner/advanced)
- Timer to track how long the user stays on the website
- Fetching and displaying GitHub repositories using API

## Responsive Design
The layout adapts to:
- Desktop (structured multi-section layout)
- Tablet (adjusted spacing and layout)
- Mobile (stacked layout for better readability)

CSS media queries ensure usability across all screen sizes.

## API Integration
The website uses the GitHub API to:
- Fetch public repositories from the user’s GitHub account
- Display repository name, description, and link
- Handle errors by showing a user-friendly message if the API fails

## State Management
State is managed using localStorage:
- Theme preference (dark/light mode)
- Visitor name (saved and displayed across sessions)

This ensures a consistent and personalized user experience.

## Deployment
The website is deployed using GitHub Pages:
- Provides a live, publicly accessible version of the application
- Allows testing and demonstration across devices and browsers

## Innovation
A Personal Highlights section was added to represent the developer’s identity, interests, and skills. This enhances the uniqueness of the portfolio and makes it more engaging and personalized.

## Limitations
- The contact form does not send data to a server (front-end only)
- API depends on internet connection and GitHub availability
- Some project links and images are placeholders

## Future Improvements
- Connect the contact form to a backend service
- Improve UI design and add more animations
- Add additional APIs for more dynamic content
- Enhance personalization features and user interaction