# Ex02 Commercial Website
## Date:16/03/2025

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FreshGlow - Online Shopping</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">FreshGlow</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Shop</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#cart">Cart</a></li>
                <li><a href="#account">Account</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home" class="hero">
        <h2>Welcome to FreshGlow</h2>
        <p>Your one-stop shop for premium products</p>
        <button onclick="location.href='#products'">Shop Now</button>
    </section>
    
    <section id="products" class="section">
        <h2>Our Products</h2>
        <div class="product-grid">
            <div class="SERUMS">
                <img src="c:\Users\admin\Desktop\SERUM.jpg" alt="SERUM">
                <h3>SERUM</h3>
                <p>Rs.239</p>
                <button>Add to Cart</button>
            </div>
            <div class="MOISTURIZER">
                <img src="c:\Users\admin\Desktop\MOIST.jpg" alt="MOISTURIZER">
                <h3>MOISTURIZER</h3>
                <p>RS.359</p>
                <button>Add to Cart</button>
            </div>
            <div class="FACEWASH">
                <img src="c:\Users\admin\Desktop\fascewash.png" alt="Face Wash">
                <h3>FACEWASH</h3>
                <p>Rs.299</p>
                <button>Add to Cart</button>
            </div>
            <div class="SUNSCREEN">
                <img src="c:\Users\admin\Desktop\sunscreen.jpg" alt="SUNSCREEN">
                <h3>SUNSCREEN</h3>
                <p>Rs.399</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>
    
    <section id="cart" class="section">
        <h2>Shopping Cart</h2>
        <p>Your cart is empty.</p>
        <button>Proceed to Checkout</button>
    </section>
    
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>We provide high-quality products with excellent customer service.</p>
    </section>
    
    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: support@FreshGlow.com | Phone: +123456789</p>
    </section>
    
    <section id="account" class="section">
        <h2>User Account</h2>
        <button>Login / Register</button>
    </section>
    
    <footer>
        <p>&copy; 2025 FreshGlow | Follow us on <a href="#">Social Media</a></p>
    </footer>
</body>
</html>
```
## style.css
```
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

body {
    background-color: #fff8f0;
    color: #444;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: linear-gradient(45deg, #ff9a8b, #ff6a88, #ff99ac);
    padding: 20px;
    color: white;
}

.logo {
    font-size: 1.8rem;
    font-weight: bold;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1rem;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #ffe5ec;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 80px 20px;
    background: linear-gradient(to right, #ffe5ec, #ffdde1);
    color: #d63384;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 20px;
}

.hero button {
    padding: 12px 24px;
    background-color: #ff6a88;
    color: white;
    border: none;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 25px;
    transition: 0.3s ease;
}

.hero button:hover {
    background-color: #ff99ac;
    color: white;
}

/* Product Section */
.product-grid {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 40px;
    flex-wrap: wrap;
}

/* Ensure all product images are the same size */
.product img {
    width: 100px; /* Set a fixed width */
    height: 100px; /* Set a fixed height */
    object-fit: cover; /* Ensure images scale properly */
    border-radius: 10px; /* Adds rounded corners */
}

.product {
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 4px 12px rgba(0, 0, 0, 0.1);
    text-align: center;
    flex: 1;
    min-width: 200px;
    max-width: 220px;
    transition: transform 0.3s ease;
}

.product:hover {
    transform: scale(1.05);
}

.product h3 {
    color: #d63384;
    margin-top: 10px;
}

.product p {
    font-size: 1rem;
    margin-bottom: 10px;
}

.product button {
    padding: 10px 20px;
    background-color: #ff6a88;
    color: white;
    border: none;
    font-size: 1rem;
    cursor: pointer;
    border-radius: 20px;
    transition: 0.3s ease;
}

.product button:hover {
    background-color: #ff99ac;
}

/* Sections */
.section {
    padding: 50px 20px;
    text-align: center;
    background-color: #fff0f6;
    margin: 20px;
    border-radius: 10px;
}

/* Footer */
footer {
    text-align: center;
    padding: 20px;
    background: linear-gradient(45deg, #ff9a8b, #ff6a88, #ff99ac);
    color: white;
    font-size: 1rem;
}

footer a {
    color: #ffe5ec;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}

/* Responsive Design */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        text-align: center;
    }

    nav ul {
        flex-direction: column;
    }

    nav ul li {
        margin: 10px 0;
    }

    .product-grid {
        flex-direction: column;
        align-items: center;
    }
}
```

## OUTPUT

![1ex](https://github.com/user-attachments/assets/e8fecaf4-e6b3-4976-87d6-dcc9d3f07f54)

![2ex](https://github.com/user-attachments/assets/16e5e9bf-1a37-4560-8971-0ba2e860e67c)

![3ex](https://github.com/user-attachments/assets/fa5e0a99-f93e-4652-b52d-e11d6fe9870a)

![4ex](https://github.com/user-attachments/assets/05a46034-06f2-4731-8f99-4f754668b1ce)

![5ex](https://github.com/user-attachments/assets/53e1f8a8-d1ab-408d-99b6-8ef8f30bc9bf)


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
