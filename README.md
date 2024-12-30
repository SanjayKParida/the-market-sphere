# The Market Sphere
[![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=fff)](#)
[![Dart](https://img.shields.io/badge/Dart-%230175C2.svg?logo=dart&logoColor=white)](#)
[![NodeJS](https://img.shields.io/badge/Node.js-6DA55F?logo=node.js&logoColor=white)](#)
[![Express.js](https://img.shields.io/badge/Express.js-%23404d59.svg?logo=express&logoColor=%2361DAFB)](#)
[![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?logo=mongodb&logoColor=white)](#)

Market Sphere is a full-fledged e-commerce platform built using Flutter for the front end and Node.js with Express.js for the backend. It consists of the following modules:

1. **[Market Sphere - Consumer App](https://github.com/SanjayKParida/market-sphere)**
2. **[Market Sphere - Vendor App](https://github.com/SanjayKParida/market-sphere-vendor)**
3. **[Market Sphere - Web Admin Panel](https://github.com/SanjayKParida/market=sphere-web-admin-panel)**
4. **[Market Sphere - Backend](https://github.com/SanjayKParida/market=sphere-backend)**

## Features
- Comprehensive e-commerce platform with role-based access.
- RESTful APIs for efficient data management.
- Responsive UI for enhanced user experience.

## Technologies
- **Frontend**: Flutter
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas

## Architecture
1. **Market Sphere - Consumer App (Flutter)**
   - A mobile application for end-users to browse and purchase products.
   - Communicates with the backend via RESTful APIs.

2. **Market Sphere - Vendor App (Flutter)**
   - A mobile application for vendors to manage products, inventory, and orders.
   - Communicates with the backend via RESTful APIs.

3. **Market Sphere - Web Admin Panel (Flutter Web)**
   - A web application for admin users to manage the overall platform, including vendors, products, and analytics.
   - Communicates with the backend via RESTful APIs.

4. **Market Sphere Backend (Node.js + Express.js)**
   - A backend server handling business logic, API endpoints, and communication with the database.
   - Serves all three frontend modules (Consumer App, Vendor App, Web Admin Panel).

5. **Database**
   - Centralized database for storing user data, product information, vendor data, and transaction logs.
   - Connected to the backend for all read/write operations.

**Data Flow:**
- The frontend applications (Consumer App, Vendor App, and Web Admin Panel) interact with the backend via secure RESTful APIs.
- The backend interacts with the database to fetch, store, and update data as per the application's requirements.

