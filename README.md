# 🏡 Nest: Campus Accommodation Platform

## 🎯 Project Overview

**Nest** is a dedicated web application designed to connect students of **[Your College Name]** with verified room and PG (Paying Guest) accommodations located near the campus.

This platform streamlines the entire process, allowing room/PG owners to register and manage their properties, and providing students with a clean, searchable interface to find, compare, and book their ideal living space. It is enhanced with a crucial "Campus Guide" feature to provide essential local information.

### ✨ Key Features

* **Dual User Portals:** Separate, secure interfaces for **Students** and **Owners/Landlords**.
* **Intuitive Search & Filter:** Students can easily search based on price, room type, amenities (Wi-Fi, AC, Mess), and distance from campus.
* **Owner Dashboard:** Owners can efficiently list properties, manage availability, and handle booking requests.
* **Campus Guide (Local Info):** An interactive map feature providing essential local points of interest, including nearest hospitals, medical stores, canteens, and transport hubs.
* **Integrated Booking System:** Simplified process for requesting and confirming room reservations.

---

## 🛠️ Technology Stack

This project is built using the following technologies:

### Frontend
* **Framework:** [e.g., React, Vue.js, Angular, or plain HTML/CSS/JavaScript]
* **Styling:** [e.g., Tailwind CSS, Bootstrap, or custom CSS]
* **State Management:** [e.g., Redux, Vuex, Context API]

### Backend
* **Language/Runtime:** [e.g., Node.js (Express), Python (Django/Flask), PHP (Laravel)]
* **Database:** [e.g., MongoDB, PostgreSQL, MySQL]
* **API:** RESTful API or GraphQL

### Deployment & Tools
* **Version Control:** Git
* **Hosting:** [e.g., Vercel, Netlify, AWS EC2]

---

## 🚀 Getting Started

Follow these steps to set up the project locally for development and testing.

### Prerequisites

You need the following software installed on your machine:
* Node.js (LTS version)
* [Database Software, e.g., MongoDB/PostgreSQL]
* Git

### Installation Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Yogendra-Bisht/ReactProjects](https://github.com/Yogendra-Bisht/ReactProjects)
    cd ReactProjects
    ```

2.  **Install Backend Dependencies:**
    ```bash
    # Navigate to the backend directory (adjust path if needed)
    cd backend
    npm install  # or pip install -r requirements.txt if Python
    ```

3.  **Install Frontend Dependencies:**
    ```bash
    # Navigate back to the root and then the frontend directory (adjust path if needed)
    cd ../frontend
    npm install
    ```

4.  **Set Up Environment Variables:**
    Create a `.env` file in both the `backend` and `frontend` directories based on the required variables.

    *Example Backend `.env` variables:*
    ```env
    PORT=5000
    MONGODB_URI=[Your Database Connection String]
    JWT_SECRET=[Your Secret Key]
    ```

5.  **Run the Application:**

    * **Start Backend Server:**
        ```bash
        cd ../backend
        npm start # or node server.js
        ```
    * **Start Frontend Client:**
        ```bash
        cd ../frontend
        npm run dev # or npm start
        ```

The application should now be accessible at `http://localhost:[Frontend Port, usually 3000]`.

---

## 🧪 Testing

To run the unit and integration tests:

```bash
# In the backend directory
npm run test:backend 

# In the frontend directory
npm run test:frontend
