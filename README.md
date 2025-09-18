# MID-TERM-PROJECT
#This a school project in preparation for the main IT project that we will do in our final year. This project is done collaboratively by USIU students; Mary Majok and Margret Wafula.

---

# Mobile Hairdressers Web Application (AfriHair) – Midterm Project

## Project Overview

This web application connects clients to mobile hairdressers in Nairobi, allowing users to book appointments, view stylist portfolios, and explore hairstyle galleries. The platform also provides a system for hairdressers to apply, manage their profiles, and showcase their work.

This project is a collaborative effort by a team of two for our midterm assignment.

---

## Features

### Client-Side

* **Sign-Up / Log-In:** Secure authentication for clients and hairdressers.
* **Booking System:** Clients can schedule appointments with available hairdressers.
* **Gallery:** Browse photos of hairstyles and stylist work.
* **Portfolio Viewing:** Explore stylist portfolios with previous works and ratings.

### Hairdresser-Side

* **Application Submission:** Apply to join the platform as a mobile hairdresser.
* **Portfolio Management:** Upload photos and manage stylist profiles.
* **Booking Management:** View and confirm client appointments.

### Admin-Side (Optional)

* Approve stylist applications
* Manage users, galleries, and bookings

---

## Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Node.js, Express
* **Database:** MongoDB
* **APIs:** RESTful endpoints for communication between frontend and backend

---

## Project Structure

```plaintext
mobile-hairdressers/
│
├── backend/
│   ├── server.js          # Express server setup
│   ├── routes/            # API routes
│   ├── controllers/       # Business logic
│   ├── models/            # MongoDB schemas
│   └── config/            # Database connection
│
├── frontend/
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── assets/            # images, icons
│
├── README.md
└── package.json
```

---

## Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/mobile-hairdressers.git
cd mobile-hairdressers
```

2. **Install backend dependencies**

```bash
cd backend
npm install
```

3. **Configure MongoDB**

* Create a MongoDB Atlas account or use a local instance
* Add your connection string in `backend/config/db.js`

4. **Run the server**

```bash
npm run dev
```

5. **Open frontend**

* Open `frontend/index.html` in your browser
* Ensure the server is running for API calls

---

## API Endpoints (Examples)

* `POST /api/users/signup` → Create new user
* `POST /api/users/login` → Log in user
* `POST /api/bookings` → Book an appointment
* `GET /api/stylists` → Get list of stylists
* `POST /api/portfolio` → Hairdresser adds portfolio item

*(Full API documentation will be provided with Swagger or Postman collection.)*

---

## Usage & Demo

### 1. **Sign-Up / Log-In**

* Clients and stylists can create accounts or log in to access their dashboards.

📷 *Screenshot placeholder: Sign-Up page*
📷 *Screenshot placeholder: Log-In page*

---

### 2. **Book a Schedule**

* Clients can choose a stylist, select a date and time, and confirm a booking.

📷 *Screenshot placeholder: Booking form*

---

### 3. **Gallery**

* Browse different hairstyles and completed works uploaded by stylists.

📷 *Screenshot placeholder: Gallery page*

---

### 4. **Apply as a Stylist**

* New hairdressers can fill out an application form to join the platform.

📷 *Screenshot placeholder: Application form*

---

### 5. **Stylist Portfolios**

* Each stylist has a profile with their work samples and reviews.

📷 *Screenshot placeholder: Portfolio page*

---

👉 To test locally:

1. Run the backend with `npm run dev`.
2. Open `frontend/index.html`.
3. Try creating an account, booking, and browsing features.

---

## Team Members

* **Member 1:** \[Mary Nyakor Majok] – Frontend development, CSS styling, UI/UX design
* **Member 2:** \[Margret Atemi Wafula] – Backend development, API integration, MongoDB database

---

## Future Improvements

* Implement user roles and access control (admin vs client vs stylist)
* Integrate email/SMS notifications for bookings
* Add payment gateway for secure transactions
* Mobile-friendly responsive design

---

## License

This project is for academic purposes and is not licensed for commercial use.

---

✨ Pro tip: When you’ve built a working version, you can replace the *Screenshot placeholders* with real images or GIF demos to really impress your lecturer.


