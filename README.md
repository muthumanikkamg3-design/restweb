# Ex.07 Restaurant Website
## Date:18/10/2025

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
administration.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - UCHIHA RESTAURENT</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>UCHIHA RESTAURENT</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <!-- Repeat for 6 people -->
    <div class="admin-card">
      <img src="madara.jpg" alt="Admin 1">
      <h3>MADARA UCHIHA</h3>
      <p>OWNER</p>
    </div>
    <div class="admin-card">
      <img src="obito.jpg" alt="Admin 2">
      <h3>OBITO UCHIHA</h3>
      <p>HEAD CHEF</p>
    </div>
    <div class="admin-card">
      <img src="itachi.jpg" alt="Admin 3">
      <h3>ITACHI UCHIHA</h3>
      <p>ASSISTANT CHEF</p>
    </div>
    <div class="admin-card">
      <img src="shishui.jpg" alt="Admin 4">
      <h3>SHISHUI UCHIHA</h3>
      <p>CASHIER</p>
    </div>
    <div class="admin-card">
      <img src="sasuke.jpg" alt="Admin 5">
      <h3>SASUKE UCHIHA</h3>
      <p>DELIVERY BOY</p>
    </div>
    <div class="admin-card">
      <img src="fugaku.jpg" alt="Admin 6">
      <h3>FUGAKU UCHIHA</h3>
      <p>CUSTOMER SERVICE</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by SAITAMA</p>
  </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - UCHIHA RESTAURENT</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>Get in Touch</h2>
    <p>📍 <strong>Address:</strong> 6,vivekandan theru,dubai kurukku sandhu,dubai main road,dubai-2434</p>
    <p>📞 <strong>Phone:</strong> (123) 01200330</p>
    <p>✉ <strong>Email:</strong> contact@uchiharestaurent.com</p>
  </section>

  <!-- Optional: Contact Form (if needed) -->
  <!--
  <section class="contact-form">
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5"></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>
  -->

  <footer>
    <p>&copy; 2025. Designed by SAITAMA</p>
  </footer>

</body>
</html>

home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - UCHIHA RESTAURENT</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>UCHIHA RESTAURENT</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="banner">
    <img src="images/banner.jpg" alt="Delicious Food Banner">
  </section>

  <section class="content">
    <h2>WELCOME</h2>
    <p>ALL ROUNDER FOODS ARE AVAILABLE.</p>
  </section>

  <footer>
    <p>&copy; 2025. Designed bY SAITAMA</p>
  </footer>
</body>
</html>

menu.html
      <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - UCHIHA RESTAURENT</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <!-- Repeat for 12 items -->
    <div class="menu-item">
      <img src="pizza.jpg" alt="Pizza">
      <h3>Cheese Pizza</h3>
      <p>DELICIOUS CHEESE PIZZA</p>
    </div>
    <div class="menu-item">
      <img src="bur.jpg" alt="Burger">
      <h3>Beef Burger</h3>
      <p>GRILLED BEEF BURGER.</p>
    </div>
    <div class="menu-item">
      <img src="pas.jpg" alt="Pasta">
      <h3>Spaghetti Carbonara</h3>
      <p>CREAMY PASTA.</p>
    </div>
    <div class="menu-item">
      <img src="sal.jpg" alt="Salad">
      <h3>Caesar Salad</h3>
      <p>CRISP LETTUCE.</p>
    </div>
    <div class="menu-item">
      <img src="sushi.jpg" alt="Sushi">
      <h3>Sushi Rolls</h3>
      <p> INCREDIBLE SUSHI.</p>
    </div>
    <div class="menu-item">
      <img src="steak.jpg" alt="Steak">
      <h3>Grilled Steak</h3>
      <p>TASTY STEAK.</p>
    </div>
    <div class="menu-item">
      <img src="tacos.jpg" alt="Tacos">
      <h3>Mexican Tacos</h3>
      <p>SPICY TACOS.</p>
    </div>
    <div class="menu-item">
      <img src="soup.jpg" alt="Soup">
      <h3>Tomato Soup</h3>
      <p>WARM AND SPICY SOUP.</p>
    </div>
    <div class="menu-item">
      <img src="sand.jpg" alt="Sandwich">
      <h3>Club Sandwich</h3>
      <p>SANDWICH OF CHICKEN.</p>
    </div>
    <div class="menu-item">
      <img src= "pan.jpg"alt="Pancakes">
      <h3>Pancakes</h3>
      <p>FLUFFY PANCAKE.</p>
    </div>
    <div class="menu-item">
      <img src="ice.jpg" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>VANNILA, CHOCOLATE, STRAWBERRY.</p>
    </div>
    <div class="menu-item">
      <img src="fries.jpg" alt="Fries">
      <h3>French Fries</h3>
      <p>CRISPY AND SPICY FRIES.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by SAITAMA</p>
  </footer>
</body>
</html>
```


## OUTPUT:
![rest2](https://github.com/user-attachments/assets/3c3076cf-1402-4138-8bf9-e69ec21b51dc)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
