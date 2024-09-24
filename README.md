# Hospital Management System

Hospital Management System is a MERN (MongoDB, Express, React, Node.js) full-stack project that includes a landing page and a dashboard.

## Features

The dashboard is designed for administrators to manage the hospital system. It consists of the following features:

-   **Admin Login**: Administrators can log in to access the dashboard.
-   **Dashboard Overview**: After logging in, the admin's name is displayed at the top, along with the number of doctors and appointments in the hospital.
-   **Appointment Management**: Administrators can view appointments in a table format. The table includes patient names and emails. Admins can perform various actions on appointments such as accept, reject, or set them to pending. They can also update appointment details.
-   **Admin Management**: Administrators have the authority to add other administrators to the system.
-   **Doctor Management**: Admins can add doctors to the system. Adding a doctor requires providing their name, email, password, department, and an image.
-   **Doctor Information**: Admins can view information about all registered doctors in the hospital.
-   **Message Management**: Admins can access and view messages sent by patients to the hospital.
-   **Logout**: Admins can log out of their accounts.

Please note that the dashboard is designed for computer screens and is not responsive for mobile or tablet devices.

## Technologies Used

-   React
-   Node.js
-   SASS
-   Bootstrap 5
-   Typescript
-   Swiper Library

**To install and use the project:**
-   Clone the repo.
-   Clone HOSPITAL-MANAGEMENT-SYSTEM-BACKEND
-   Add in `./backend/config/config.env`:
    -   `mongo_uri` to your database.
    -   `CLOUDINARY_CLOUD_NAME`, `CLOUDINARY_API_SECRET`, and `CLOUDINARY_API_KEY`.
-   In `./backend` & `npm install` & `npm run build`.
-   In `./dashboard` & `npm install` & `npm run build`.
-   Then `./backend/npm start`.

---

Copyright © CodeWithZeeshu
https://www.youtube.com/@CodeWithZeeshu

---