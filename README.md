# Stripe Payment Integration

This project implements a **secure Stripe Checkout payment flow** using **Node.js** and **Express** in test mode. It demonstrates backend session creation, protected API key management with environment variables, and real-time transaction tracking through the Stripe Dashboard.

---

## Project Structure

Stripe Payment Gateway/
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
├── server.js
└── Screenshots/
└── dashboard.png

markdown
Copy code

- `.gitignore` – To ignore sensitive files like `.env`.  
- `index.html` – Frontend page for Stripe checkout.  
- `server.js` – Backend Node.js server handling Stripe sessions.  
- `package.json` – Project dependencies.  
- `Screenshots/dashboard.png` – Screenshot of Stripe Dashboard.  

> **Note:** Make sure your `.env` file is added to `.gitignore` to keep API keys secure.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Monicram/Stripe-Payment-Integration.git
cd "Stripe Payment Gateway"
Install dependencies:

bash
Copy code
npm install
Create a .env file in the root directory with your Stripe API keys:

ini
Copy code
STRIPE_SECRET_KEY=your_secret_key_here
STRIPE_PUBLISHABLE_KEY=your_publishable_key_here
Running the Project
Start the server:

bash
Copy code
node server.js
Open index.html in your browser to test the Stripe checkout flow.

Dashboard Screenshot
Below is a screenshot of the Stripe Dashboard showing sample transactions and payment session tracking:


Tip: Place the image in the folder named Screenshots inside your project directory so the path matches exactly:
Stripe Payment Gateway/Screenshots/dashboard.png

Features
Secure Stripe checkout session creation.

Environment variable management for API keys.

Real-time transaction monitoring via Stripe Dashboard.

Easy to deploy and test in development mode.


```bash
git add README.md Screenshots/dashboard.png
git commit -m "Add README with Stripe Dashboard screenshot"
git push
