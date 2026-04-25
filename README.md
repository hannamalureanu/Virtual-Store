# 🛍️ Hanna Boutique – Online Store Project

## 📌 Overview

Hanna Boutique is a web-based e-commerce application that allows users to browse products, manage a shopping cart, and interact with a dynamic and responsive interface.

---

## 🚀 Technologies Used

* **Frontend:** HTML5, CSS3, JavaScript
* **Backend:** PHP (sessions & form processing)
* **Database:** MySQL
* **Server:** Apache (via XAMPP)
* **Security:** PHP sessions, form validation, output escaping

---

## 🗄️ Database Architecture

```
hanna_db/
├── produse 
│   ├── codp
│   ├── nume
│   ├── pret
│   ├── descriere
│   ├── imagine
│   └── tip

└── Cart (managed via PHP sessions)
    ├── codp
    ├── nume
    ├── pret
    ├── cantitate
    ├── imagine
    └── subtotal
```

---

## ✨ Main Functionalities

1. **Product Catalog**

   * Display products by category
   * Includes images, prices, and short descriptions

2. **Shopping Cart System**

   * Add products to cart
   * Update quantities
   * Remove items

3. **Modern User Interface**

   * Clean and elegant design
   * Visual notifications for user actions

4. **AJAX Integration**

   * Add to cart without page reload

5. **Responsive Design**

   * Optimized for mobile and desktop devices

6. **JavaScript Fallback**

   * Full functionality even if JavaScript is disabled

---

## 📁 Project Structure

```
hanna_boutique/
├── index.php              # Main page with categories
├── categorie.php          # Product pages by category
├── cos.php                # Shopping cart management
├── adauga_cos.php         # Add to cart logic (AJAX + fallback)
├── creare.sql             # Database structure and demo data

├── css/
│   ├── style.css          # General styles
│   ├── products.css       # Product page styles
│   └── cart.css           # Cart page styles

├── js/
│   └── cart.js            # JavaScript cart functionality

├── imagini/               # Product images and assets
```

---

## ⚙️ Setup & Installation

1. Install XAMPP and start **Apache** and **MySQL**
2. Import `creare.sql` into your MySQL database
3. Place the project folder in:

   ```
   htdocs/
   ```
4. Access the project in your browser:

   ```
   http://localhost/hanna_boutique
   ```

---

## 📷 Features Preview

* Dynamic product catalog
* Interactive shopping cart
* Smooth user experience with AJAX
* Mobile-friendly design

---

## 📌 Future Improvements

* User authentication system
* Admin dashboard
* Payment integration
* Product search and filters

---

## 👨‍💻 Author

Developed as a web development project focused on building a functional and modern e-commerce application.
