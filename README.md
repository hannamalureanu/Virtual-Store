# Virtual Store
Design and implementation of a virtual store where products are stored in a database. The store has several categories. For each product, the name, price, description and image are stored and displayed. It is possible to specify the quantity when purchasing. It is possible to purchase multiple products from the same category simultaneously.

Technologies used 
• Frontend: HTML5, CSS3, JavaScript 
• Backend: PHP with sessions and form processing 
• Database: MySQL 
• Server: Apache via XAMPP 
• Security: PHP sessions, form validation, output escaping 
Database architecture 
hanna_db/ 
├── products (code, name, price, description, image, type) 
└── Cart managed through PHP sessions (code, name, price, quantity, image, subtotal) 
Main functionalities 
1. Product catalog: Display by category with images, price and short descriptions 
2. Cart system: Add, update quantities and delete products 
3. Modern user interface: Elegant design with visual notifications 
4. AJAX experience: Add to cart without reloading the page 
5. Responsive design: Adaptable interface for mobile devices 
6. Fallback for JavaScript: Full functionality and no JS 
Code structure 
hanna_boutique/ 
├── index.php # Main page with categories 
├── categorie.php 
# Product pages by category 
├── cos.php # Shopping cart management 
├── adauga_cos.php 
# Add to cart logic (AJAX + fallback) 
├── cart.js # JavaScript for cart interaction 
├── creare.sql
├── css/ 
│ 
# Database structure and demo data 
├── style.css # General styles 
│ 
├── products.css # Product page styles 
│ └── cart.css # Cart page styles 
├── images/ # Product graphic resources 
└── js/ 
└── cart.js # JavaScript functions for cart
