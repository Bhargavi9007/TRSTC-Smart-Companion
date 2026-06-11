# TRSTC-Smart-Companion
# SmartBus Telangana – AI-Powered Public Transport Navigation System

## Overview

SmartBus Telangana is a MERN Stack-based web application designed to help passengers easily search, discover, and navigate TSRTC bus services across Telangana. The platform provides route information, bus number search, source-to-destination route discovery, ETA prediction, favorite route management, and map-based visualization.

The primary goal of this project is to solve the common problem faced by students, employees, and travelers who depend on public transportation but often lack access to accurate route information and bus availability details.

## Problem Statement

Many passengers in Telangana rely on TSRTC buses for daily transportation. However, finding suitable buses, routes, intermediate stops, and estimated arrival information can be difficult. Existing solutions may not provide complete coverage for all locations or may not be optimized for Telangana-specific transportation needs.

SmartBus Telangana addresses this issue by providing a centralized platform where users can search for buses, discover routes, and visualize travel information through an interactive map interface.

## Objectives

* Provide source-to-destination bus route search.
* Enable bus number-based route lookup.
* Display route details and intermediate stops.
* Integrate map-based route visualization.
* Offer ETA prediction for buses.
* Allow users to save frequently used routes.
* Create a scalable architecture that can support real-time tracking in the future.

## Features

### Bus Number Search

Users can search for a specific TSRTC bus number and view its route details.

### Source and Destination Search

Users can enter any source and destination location to discover available bus routes.

### Smart Location Search

Location suggestions are provided dynamically as users type, similar to modern map applications.

### Interactive Maps

Routes and stops are displayed using map integration for better visualization.

### Favorite Routes

Users can save frequently searched routes for quick access.

### ETA Prediction

The system provides estimated arrival times based on route information.

### Responsive Design

The application is designed to work seamlessly across desktop, tablet, and mobile devices.

## Technology Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Axios
* React Router DOM
* Leaflet.js

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### APIs & Services

* OpenStreetMap
* Nominatim API

### Deployment

* Vercel (Frontend)
* Render (Backend)

## System Architecture

Frontend (React.js)
↓
REST API (Express.js)
↓
MongoDB Atlas
↓
OpenStreetMap Services

## Future Enhancements

* Real-time bus GPS tracking
* AI-based route recommendations
* Traffic-aware ETA prediction
* Mobile application support
* Notification system for bus arrivals
* Integration with official TSRTC APIs
* Crowdsourced live bus updates

## Conclusion

SmartBus Telangana aims to improve the public transportation experience by providing an intelligent and user-friendly platform for bus route discovery and navigation. The project demonstrates the practical implementation of the MERN Stack while addressing real-world transportation challenges faced by passengers across Telangana.
