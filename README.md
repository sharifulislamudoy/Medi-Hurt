# Medi-Hurt

![Medi-Hurt Logo](https://medi-hurt.web.app/favicon.ico)

**Medi-Hurt** is a multi-vendor e-commerce platform specializing in the sale of medicines and healthcare products. Built with the MERN stack (MongoDB, Express.js, React.js, Node.js), it offers users a seamless and secure experience for browsing, purchasing, and managing medicines with features tailored for admins, sellers, and users.

---

## Live Site
🌐 [https://medi-hurt.web.app/](https://medi-hurt.web.app/)

---

## Project Overview

Medi-Hurt is designed to support multiple vendors (sellers) to list medicines and healthcare products while allowing users to easily browse, select, and purchase medicines online. The platform incorporates user authentication, role-based dashboards, real-time updates, responsive design, and secure payment via Stripe.

---

## Admin Credentials

- **Email:** admin@medi-hurt.com  
- **Password:** Admin1234  

## Seller Credentials

- **Email:** seller@medi-hurt.com  
- **Password:** Seller1234  

---

## Features

- **User Roles:** Supports Admin, Seller, and User roles with dedicated dashboards.
- **Multi-Vendor System:** Sellers can manage their medicines and advertisement requests.
- **Medicine Categories:** Categorized medicines with detailed listings and filters.
- **Responsive Design:** Fully responsive for mobile, tablet, and desktop devices.
- **Authentication:** Email-password login and social login with Google and GitHub.
- **Private Routes:** Persistent authentication with access tokens stored securely.
- **Product Management:** Admin and Sellers can add, update, and delete medicines and categories.
- **Advertisement Slider:** Admin controls featured medicines displayed in homepage slider.
- **Shopping Cart & Checkout:** Users can add medicines to cart, adjust quantities, and pay securely via Stripe.
- **Order Invoice:** Automatically generated, printable PDF invoice after checkout.
- **Sales Reporting:** Admin can generate detailed sales reports with filtering and export options (PDF, Excel, CSV).
- **Payment Management:** Track pending and completed payments, approve payments from the admin dashboard.
- **Pagination, Sorting, and Search:** All medicine listings support pagination, sorting by price, and search by multiple fields.
- **Notifications:** Sweet alert/toast notifications for CRUD operations and authentication events.
- **Secure Environment Variables:** Firebase config and MongoDB credentials hidden in environment variables.
- **Internationalization (Optional):** Supports multiple languages.
- **Additional Utilities:** Dynamic page titles using react-helmet and a digital clock in the navbar.

---

## Tech Stack

- **Frontend:** React.js, React Router, Tailwind CSS, DaisyUI, TanStack Query, React Hook Form, React Helmet, SweetAlert2, Swiper.js  
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, JWT Authentication  
- **Authentication:** Firebase Authentication (email/password, Google, GitHub)  
- **Payments:** Stripe API for secure payments  
- **Deployment:** Firebase Hosting (Frontend), Vercel (Backend)  
- **Other:** PDF generation, Excel/CSV export, Pagination, Sorting, Search  

---

## Repositories

- **Client (Frontend):** [https://github.com/sharifulislamudoy/Medi-Hurt-Client](https://github.com/sharifulislamudoy/Medi-Hurt-Client)  
- **Server (Backend):** [https://github.com/sharifulislamudoy/Medi-Hurt-Server](https://github.com/sharifulislamudoy/Medi-Hurt-Server)  

---

## Installation and Setup

### Install dependencies:

- For Client:

```bash
cd Medi-Hurt-Client
npm install
- For Server: 

```bash
cd Medi-Hurt-Server 
npm install
## Environment variables:
- For Client:
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
REACT_APP_SERVER_URL=http://localhost:5000
- For Server:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
## Contribution:
This project was developed by Shariful Islam Udoy as an assignment and personal portfolio project. Contributions are welcome via pull requests and issues to improve functionality, add features, or fix bugs. Please follow standard GitHub workflow for contributing.
## Contact:
Developer: Shariful Islam Udoy
GitHub: https://github.com/sharifulislamudoy
Email: sharifulislam.udoy@example.com
##Thank you for visiting Medi-Hurt! Your health, our priority.
---
