
---

🩺 Prescripto – Doctor Appointment Web App

Prescripto is a full-stack MERN application that simplifies doctor appointment booking with role-based access for Patients, Doctors, and Admins. It supports secure online payments via Stripe and Razorpay, making healthcare access smoother and less painful than waiting rooms.


---

🚀 Features

🔐 Role-Based Authentication (JWT)

Patient

Book, cancel, reschedule appointments

Pay via Cash / Stripe / Razorpay

Manage profile & history


Doctor

Manage appointments

View earnings & dashboard stats

Update profile & availability


Admin

Manage doctors & appointments

View platform analytics

Add/edit/remove doctors




---

💳 Payments

Cash

Stripe

Razorpay
Secure, reliable, and less likely to ruin your day than most payment systems.



---

🛠️ Tech Stack

Frontend: React.js

Backend: Node.js + Express.js

Database: MongoDB

Auth: JWT



---

🌐 Core Pages

Home (search + top doctors)

Doctor Listing & Filtering

Appointment Booking

User Profile

Admin Dashboard

Doctor Dashboard



---

⚙️ Setup

git clone https://github.com/your-username/prescripto.git
cd prescripto

npm install
cd client && npm install

Environment Variables

MONGO_URI=your_mongo_uri
JWT_SECRET=your_secret
STRIPE_API_KEY=your_key
RAZORPAY_API_KEY=your_key

npm run dev


---

📁 Structure

client/        # React frontend
server/        # Node backend
models/        # DB schemas

---

👨‍💻 Developer

Built with persistence (and probably questionable sleep cycles) by
Ayaan Shaikh

Designed and developed full-stack architecture

Implemented secure authentication & role-based access

Integrated payment gateways

Built scalable dashboards for admin & doctors



---

📌 Notes

Clean separation of concerns

Production-ready structure

Easily extendable (notifications, AI triage, etc.)



---