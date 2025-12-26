# Ex.07 Restaurant Website
## Date:22/12/2025

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
<!DOCTYPE html>
<html>
  <head>
    <title>Foodie's Delight</title>
    <style>
      body {
        margin: 10;
        font-family: Arial;
        background: #f4f4f4;
      }

      header {
        background: #8b0000;
        color: white;
        padding: 30px;
        text-align: center;
        font-size: 40px;
      }

      nav {
        background: #333;
        text-align: center;
      }

      nav a {
        color: white;
        padding: 15px;
        display: inline-block;
        text-decoration: none;
      }

      nav a:hover {
        background: orange;
        color: black;
      }

      section {
        padding: 30px;
        text-align: center;
      }

      .menu {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
      }

      .item {
        background: rgb(247, 242, 242);
        padding: 15px;
        border-radius: 5px;
      }

      .item img {
        width: 70%;
        height: 150px;
        border-radius: 5px;
      }

      footer {
        background: #333;
        color: rgb(255, 255, 255);
        text-align: center;
        padding: 10px;
      }

      .admin-grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
        margin-top: 10px;
      }

      .admin-card {
        background-color: rgb(252, 252, 252);
        padding: 15px;
        text-align: center;
        border-radius: 2px;
      }

      .admin-card img {
        width: 50%;
        height: 300px;
        object-fit: cover;
        border-radius: 5px;
      }
    </style>
  </head>

  <body>
    <header>Spicy Treat Restaurant</header>

    <nav>
      <a href="#home">Home</a>
      <a href="#menu">Menu</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>

    <section id="home">
      <h2>Welcome</h2>
      <p>Delicious food made with love and tradition.</p>
    </section>

    <section id="menu">
      <h2>Our Menu</h2>
      <div class="menu">
        <div class="item">
          <img src="momos.png" />
          <p>Momos</p>
        </div>
        <div class="item">
          <img src="pizza.png" />
          <p>Veg Pizza</p>
        </div>
        <div class="item">
          <img src="burgar.png" />
          <p>Burgar</p>
        </div>
        <div class="item">
          <img src="pasta.png" />
          <p>Pasta</p>
        </div>
        <div class="item">
          <img src="biriyani.png" />
          <p>Chicken Biriyani</p>
        </div>
        <div class="item">
          <img src="prawn.png" />
          <p>Prawn Parotta</p>
        </div>
      </div>
    </section>

    <section id="admin">
      <h2>Administration</h2>
      <div class="admin-grid">
        <div class="admin-card">
          <img src="pic1.png" />
          <h3>Aravind</h3>
          <p>Manager</p>
        </div>

        <div class="admin-card">
          <img src="pic2.png" />
          <h3>Catherine</h3>
          <p>Chef</p>
        </div>

        <div class="admin-card">
          <img src="pic3.png" />
          <h3>Arun Das</h3>
          <p>Marketing Head</p>
        </div>

        <div class="admin-card">
          <img src="pic4.png" />
          <h3>Neha</h3>
          <p>HR Executive</p>
        </div>

        <div class="admin-card">
          <img src="pic5.png" />
          <h3>Karthick</h3>
          <p>Finance Officer</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Thiruvallur,Tamil Nadu</p>
      <p>Ph:9876543210</p>
    </section>
    <footer>Designed by BHARGAVI S</footer>
  </body>
</html>
```
## OUTPUT:

<img width="1807" height="775" alt="Screenshot 2025-12-26 102629-1" src="https://github.com/user-attachments/assets/6ca52446-1712-45c5-8948-e5a644a8bc3a" />
<img width="1807" height="775" alt="Screenshot 2025-12-26 102629-1" src="https://github.com/user-attachments/assets/f3260841-7c90-4f75-a861-39a04d9024b2" />

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
