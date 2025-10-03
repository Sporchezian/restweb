# Ex.07 Restaurant Website

## Date:03/10/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<<<<<<< HEAD
index.html:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tasty Bites Restaurant</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fafafa;
        }

        header {
            background-color: #d9534f;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #333;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            display: block;
        }

        nav a:hover {
            background-color: #575757;
        }

        .hero {
            background-image: url('https://via.placeholder.com/1200x400');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 2rem;
            font-weight: bold;
            text-shadow: 2px 2px 4px #000;
        }

        .container {
            padding: 20px;
        }

        .menu-item {
            border-bottom: 1px solid #ddd;
            padding: 10px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>The Grill</h1>
    <p>Delicious food made with love</p>
    
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
    Welcome to Tasty Bites!
</div>

<div class="container" id="menu">
    <h2>Our Menu</h2>
    
    <div class="menu-item">
        <h3>Margherita Pizza - $8</h3>
        <p>Classic delight with fresh mozzarella and basil.</p>
    </div>

    <div class="menu-item">
        <h3>Pasta Alfredo - $10</h3>
        <p>Creamy pasta with garlic and parmesan.</p>
    </div>

    <div class="menu-item">
        <h3>Veg Burger - $6</h3>
        <p>Juicy patty with fresh veggies and sauce.</p>
    </div>
</div>

<div class="container" id="about">
    <h2>About Us</h2>
    <p>
        Tasty Bites is a family-owned restaurant serving fresh and flavorful dishes.
        We believe in quality ingredients and exceptional service.
    </p>
</div>

<div class="container" id="contact">
    <h2>Contact Us</h2>
    <p>📍 Location: 123 Main Street, Your City</p>
    <p>📞 Phone: +91 9876543210</p>
    <p>📧 Email: contact@tastybites.com</p>
</div>

<footer>
    © 2025 Tasty Bites Restaurant. All Rights Reserved.
</footer>

</body>
</html>

  
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tasty Bites Restaurant</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fafafa;
        }

        header {
            background-color: #d9534f;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #333;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            display: block;
        }

        nav a:hover {
            background-color: #575757;
        }

        .hero {
            background-image: url('https://via.placeholder.com/1200x400');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 2rem;
            font-weight: bold;
            text-shadow: 2px 2px 4px #000;
        }

        .container {
            padding: 20px;
        }

        .menu-item {
            border-bottom: 1px solid #ddd;
            padding: 10px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>The Grill</h1>
    <p>Delicious food made with love</p>
    
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#menu">Menu</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
    Welcome to Tasty Bites!
</div>

<div class="container" id="menu">
    <h2>Our Menu</h2>
    
    <div class="menu-item">
        <h3>Margherita Pizza - $8</h3>
        <p>Classic delight with fresh mozzarella and basil.</p>
    </div>

    <div class="menu-item">
        <h3>Pasta Alfredo - $10</h3>
        <p>Creamy pasta with garlic and parmesan.</p>
    </div>

    <div class="menu-item">
        <h3>Veg Burger - $6</h3>
        <p>Juicy patty with fresh veggies and sauce.</p>
    </div>
</div>

<div class="container" id="about">
    <h2>About Us</h2>
    <p>
        Tasty Bites is a family-owned restaurant serving fresh and flavorful dishes.
        We believe in quality ingredients and exceptional service.
    </p>
</div>

<div class="container" id="contact">
    <h2>Contact Us</h2>
    <p>📍 Location: 123 Main Street, Your City</p>
    <p>📞 Phone: +91 9876543210</p>
    <p>📧 Email: contact@tastybites.com</p>
</div>

<footer>
    © 2025 Tasty Bites Restaurant. All Rights Reserved.
</footer>

</body>
</html>

  
``
## OUTPUT:

![alt text](<Screenshot 2025-10-03 194628.png>)
![alt text](<Screenshot 2025-10-03 194647.png>)
![alt text](<Screenshot 2025-10-03 194659.png>)
![alt text](<Screenshot 2025-10-03 194725.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
