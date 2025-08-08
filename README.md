# 🌟 Prescripto - Doctor Appointment Web App

**Prescripto** is a modern, full-stack healthcare web application built to **streamline the process of booking doctor appointments** for patients while offering powerful management tools for doctors and administrators.

With **three dedicated user roles** — **Patient**, **Doctor**, and **Admin** — Prescripto ensures each user gets a personalized, role-specific experience. Integrated with **Stripe** and **Razorpay** payment gateways, it guarantees secure, smooth, and convenient online transactions.

Built on the **MERN stack** (**MongoDB**, **Express.js**, **React.js**, **Node.js**), Prescripto is designed for **speed, reliability, and scalability**.

---

## 🛠️ Tech Stack

| Layer        | Technology Used           |
| ------------ | ------------------------- |
| **Frontend** | React.js, CSS, JavaScript |
| **Backend**  | Node.js, Express.js       |
| **Database** | MongoDB                   |
| **Payments** | Stripe, Razorpay          |
| **Auth**     | JSON Web Token (JWT)      |

---

## 🔑 Key Features

### 1. Role-Based Access & Authentication

* **Patient**:

  * Sign up, log in, and manage appointments.
  * Book, cancel, or reschedule appointments.
  * Multiple payment options — **Cash, Stripe, Razorpay**.
  * Maintain a personal profile with editable details (name, email, gender, address, DOB, profile picture).

* **Doctor**:

  * View and manage appointments in an intuitive dashboard.
  * See earnings, patient count, and recent bookings at a glance.
  * Update professional details (fees, description, address, availability).
  * Access patient details for upcoming consultations.

* **Admin**:

  * Manage the complete doctor database.
  * View **analytics** on total doctors, patients, appointments, and latest bookings.
  * Add, edit, or delete doctor profiles.
  * Oversee all appointments — cancel or mark as completed.

---

## 🏠 Core Pages & Functionality

### Home Page

* Quick doctor search by specialty.
* Display of **top doctors** with profile previews.
* Additional sections: *About Us, Delivery Info, Privacy Policy, Contact Us*.
* Clean footer with navigation links.

### All Doctors Page

* View all registered doctors.
* **Specialty-based filtering** for quick navigation.
* Click-through to **Doctor Appointment Page** for booking.

### About Page

* Highlights **Prescripto’s mission** and *Why Choose Us*:

  * **Efficiency** – streamlined booking.
  * **Convenience** – easy online payments.
  * **Personalization** – tailored experience.

### Contact Page

* Contact details, office address, and career opportunities.
* Footer navigation included.

### Doctor Appointment Page

* Detailed doctor profile: photo, qualifications, experience, description.
* Appointment booking form: choose **date**, **time**, and **payment method**.
* Payment options: **Cash**, **Stripe**, **Razorpay**.
* Suggested related doctors at the bottom.
* Login/signup required before booking.

### User Profile

* View and edit profile details.
* Upload profile picture.
* View past and upcoming appointments.
* Logout functionality.

---

## 📊 Admin Panel

* **Dashboard**:

  * Stats for doctors, patients, appointments.
  * Latest bookings overview.
* **Doctor Management**:

  * Add doctors with details (specialty, image, degree, experience, fees, etc.).
  * Edit or remove existing doctor profiles.
* **Appointment Management**:

  * Complete view of all bookings.
  * Actions: *Cancel* or *Mark as Completed*.

---

## 🩺 Doctor Dashboard

* **Earnings Overview** — total income from completed appointments.
* **Appointments List** — with patient details, date, time, and status.
* **Profile Management** — update fees, description, address, availability.

---

## 💳 Payment Integration

* **Multiple Modes Supported**:

  * Cash
  * Stripe (credit/debit card payments)
  * Razorpay (UPI, wallets, net banking)
* Fully secure payment workflow.

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/prescripto.git
cd prescripto
```

### 2️⃣ Install Dependencies

```bash
npm install
cd client
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_API_KEY=your_stripe_api_key
RAZORPAY_API_KEY=your_razorpay_api_key
```

### 4️⃣ Start the Application

```bash
npm run dev
```

---

## 📂 Folder Structure

```plaintext
prescripto/
├── client/          # Frontend (React.js)
├── server/          # Backend (Node.js, Express.js)
├── models/          # MongoDB Schemas
├── controllers/     # API Controllers
├── routes/          # API Routes
├── middleware/      # Authentication & Error Handling
├── config/          # Configuration Files
├── utils/           # Utility Functions
├── public/          # Static Files
└── .env             # Environment Variables
```

---

## 🤝 Contributing

We welcome contributions of any kind — bug fixes, features, or documentation improvements.
**Steps**:

1. Fork this repo
2. Create a new branch (`feature-branch`)
3. Commit your changes
4. Open a Pull Request

---

## 🌟 Acknowledgements

Special thanks to the creators and maintainers of:

* **MongoDB**
* **Express.js**
* **React.js**
* **Node.js**
* **Stripe**
* **Razorpay**

---

MIT License  © 2025 **Kumari Siddhi**
