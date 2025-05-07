# 🚀 UDAAN: Empowering Children of Sex Workers

**Udaan Demo :** **https://www.youtube.com/watch?v=QSJ4mAZvMoU**

**Udaan** is a comprehensive web platform dedicated to supporting the educational, emotional, and vocational needs of children of sex workers. It offers centralized access to schooling resources, mentorship, counseling, and a secure fundraising portal—all aimed at breaking the cycle of marginalization and building sustainable futures.

---

## 🗂️ Features

- **User Registration & Management**  
  Secure sign-up and profile management for children, mentors, volunteers, and donors.

- **Educational & Career Support**  
  Structured access to secondary education resources, vocational training modules, and scholarship guidance.

- **Emotional & Psychological Counseling**  
  Confidential chat and appointment scheduling with trained counselors.

- **Secure Fundraising & Sponsorship**  
  Online donation portal with automated receipt generation via email.

- **AI Chatbot Assistance**  
  Voiceflow-powered webchat widget delivering instant answers on platform navigation and resources.

- **Impact Dashboard**  
  Real-time metrics on beneficiaries served, funds raised, and program outcomes.

---

## 🛠️ Tech Stack & Usage

- **HTML5 & Semantic Markup**  
  Implemented with semantic elements (`<header>`, `<section>`, `<article>`, `<footer>`) to improve accessibility and SEO.

- **CSS3 & Flexbox Layout**  
  Responsive design achieved using CSS3 Flexbox for one-dimensional layouts across devices.

- **JavaScript (Vanilla)**  
  Client-side validation, dynamic content updates, and AJAX calls powered by ES6+ JavaScript.

- **Node.js & Express**  
  - Node.js: Event-driven JavaScript runtime on V8 engine for building the server.  
  - Express: Minimalist web framework providing robust routing and middleware support.

- **PostgreSQL**  
  Relational database for persisting user profiles, educational records, and transaction logs.

- **Python (smtplib)**  
  Automated email receipts and notifications using Python’s built-in smtplib module.

- **Razorpay Integration**  
  Secure payment processing via Razorpay’s Node.js SDK, handling order creation and webhook verification.

- **Voiceflow Webchat**  
  Embedded Voiceflow webchat widget for conversational AI assistance on the site.

---

## ⚙️ Installation

### Clone the Repository
```bash
git clone https://github.com/1543siddhant/UDAAN-Web-Main.git
cd UDAAN-Web-Main
```

### Backend Setup
```bash
cd backend
npm install  # Installs Express, Razorpay SDK, pg, etc.
```

### Environment Variables

Create a `.env` file in the `backend/` directory:
```ini
PORT=3000
DB_URL=postgresql://<user>:<pass>@localhost:5432/udaan
RAZORPAY_KEY_ID=<your_key>
RAZORPAY_KEY_SECRET=<your_secret>
SMTP_HOST=<smtp_host>
SMTP_PORT=587
SMTP_USER=<your_email>
SMTP_PASS=<your_email_password>
```

### Database Initialization
```bash
psql -U <user> -d udaan -f schema.sql
```

### Start Backend
```bash
npm start
```

### Front-end Preview
In the project root:
```bash
npx serve ./frontend
```
Visit: [http://localhost:5000](http://localhost:5000)

---

## 🎯 Usage

1. Register as a child, mentor, volunteer, or donor.
2. Explore the dashboard to track progress, make a test donation, and chat with the AI assistant.
3. View impact metrics and testimonials in real time.

---

## 🤝 Contributing

Contributions are welcome!

```bash
# Fork the repository
git checkout -b feature/my-feature     # Create feature branch
git commit -m "Add my feature"         # Commit changes
git push origin feature/my-feature     # Push to the branch
```

Then, open a Pull Request.

---


## 📬 Contact

**Siddhant Patil** – siddhantpatil1543@gmail.com
GitHub: [1543siddhant/UDAAN-Web-Main](https://github.com/1543siddhant/UDAAN-Web-Main)
