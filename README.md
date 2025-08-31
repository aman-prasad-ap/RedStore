# RedStore — E-Commerce Website

[![Preview](assets/images/preview.png)](https://redmart.netlify.app/)

A **responsive e-commerce website** built with **HTML, CSS, JavaScript, and PHP**, integrated with **Razorpay API** for secure online payments.  

---

## 🚀 Project Overview

**RedStore** is a complete e-commerce storefront prototype that includes:
- Product catalog
- Product details page
- Shopping cart
- Checkout system with payment integration  

It’s built to demonstrate **full-stack web development** concepts with a working **payment flow**.

---

## ✨ Features

- 🛍️ Product listing & detail pages  
- 🛒 Shopping cart with quantity update  
- 💳 Secure payment integration via **Razorpay API** (backend in PHP)  
- 📱 Fully responsive (works on mobile, tablet, desktop)  
- ⚡ Lightweight & easy to deploy on **XAMPP/WAMP/LAMP**  

---

## 🔗 Live Demo

- 🌐 **Frontend Demo (Netlify):** [https://redmart.netlify.app/](https://redmart.netlify.app/)  
  *(Note: This is only the **frontend version**. PHP backend and Razorpay payment integration are not supported on Netlify, so the checkout/payment flow will not work here.)*  

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript  
- **Backend:** PHP 7+  
- **Database (optional):** MySQL (if used for products/users)  
- **Payment Gateway:** [Razorpay API](https://razorpay.com/docs/api/)  
- **Local Server:** XAMPP (Apache + PHP + MySQL)  

---

## 📂 Project Structure

RedStore/
├── index.php              # Homepage
├── products.php           # Product Listing
├── product-details.php    # Product Details
├── cart.php               # Shopping Cart
├── checkout.php           # Checkout Page
├── payment.php            # Razorpay integration backend
├── config.php             # Database / API Configurations
│
├── css/
│   └── style.css          # Styling
│
├── js/
│   └── main.js            # Frontend interactivity
│
├── assets/
│   └── images/            # Product & UI images
│
└── README.md


---

## ⚙️ Setup & Running Locally

1. Install [XAMPP](https://www.apachefriends.org/) or WAMP and start **Apache** & **MySQL**.  
2. Clone this repository into your `htdocs` folder:

   ```bash
   git clone https://github.com/aman-prasad-ap/RedStore.git
3. Place the project inside:

   C:/xampp/htdocs/RedStore

4. Configure your Razorpay API credentials in config.php:

  $razor_api_key = "YOUR_KEY_HERE";
  $razor_api_secret = "YOUR_SECRET_HERE";


5. Access the project in your browser:

  http://localhost/RedStore/
  <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c87873d2-7b71-49f3-91f0-69d38c9b4cec" />
  <img width="1864" height="902" alt="image" src="https://github.com/user-attachments/assets/eb676b12-0abf-462f-a7fb-e6a8417d0466" />
  <img width="1889" height="909" alt="image" src="https://github.com/user-attachments/assets/b56837c4-4ecd-43d2-a924-506fa661a26b" />


🤝 Contributing

1. Fork this repo
2. Create a new branch (feature/new-feature)
3. Commit changes and push
4. Open a Pull Request

---

### 🔧 Suggested Changes for You
1. **Replace Preview Image**  
   - Current: `https://via.placeholder.com/600x300?text=RedStore+Preview`  
   - Suggestion: Add a real screenshot of your homepage inside `/assets/images/` and link it here.  

2. **Add Real Screenshots in "📸 Screenshots" Section**  
   - Capture:  
     - Homepage  
     - Product Details Page  
     - Cart  
     - Checkout Page  
   - Upload them to `/assets/images/screenshots/` and embed with Markdown like:  
     ```markdown
     ![Homepage](assets/images/screenshots/home.png)
     ```

3. **Optional**: Add a **Deployment Section**  
   - Explaining that PHP version must be hosted on a server (000webhost, Hostinger, etc.), while frontend works fine on Netlify.  

---

👉 This README now highlights:
- Your **PHP backend**  
- **Razorpay integration**  
- Clear **setup instructions** (with XAMPP)  

---
