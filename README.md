# Ex02 Commercial Website
## Date: 14-08-2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Watch Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f9fa;
      color: #333;
    }

    /* Navbar */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #111;
      padding: 15px 50px;
      color: #fff;
    }
    .navbar h1 {
      font-size: 24px;
      letter-spacing: 2px;
    }
    .navbar ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }
    .navbar ul li {
      display: inline;
    }
    .navbar ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }

    /* Hero Section */
    .hero {
      background: url('wrist-watch-water-drops-reflection-260nw-302011454.webp') no-repeat center center/cover;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      text-shadow: 2px 2px 5px black;
    }
    .hero h2 {
      font-size: 48px;
    }

    /* Products Section */
    .products {
      padding: 50px;
    }
    .products h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 32px;
    }
    .product-grid {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }
    .product-card {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      width: 280px;
      padding: 20px;
      text-align: center;
      transition: transform 0.3s;
    }
    .product-card:hover {
      transform: translateY(-5px);
    }
    .product-card img {
      width: 100%;
      border-radius: 8px;
    }
    .product-card h3 {
      margin: 15px 0 10px;
      font-size: 20px;
    }
    .product-card p {
      font-size: 16px;
      color: #777;
    }
    .price {
      font-size: 18px;
      font-weight: bold;
      color: #e63946;
    }
    .buy-btn {
      margin-top: 10px;
      display: inline-block;
      padding: 10px 20px;
      background: #111;
      color: #fff;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }
    .buy-btn:hover {
      background: #e63946;
    }

    /* Footer */
    .footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #fff;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <div class="navbar">
    <h1>WatchStore</h1>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Brands</a></li>
      <li><a href="#">Offers</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </div>

  <!-- Hero Section -->
  <div class="hero">
    <h2>Luxury Watches for Every Style</h2>
  </div>

  <!-- Products Section -->
  <div class="products">
    <h2>Our Collection</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1523170335258-f5ed11844a49?auto=format&fit=crop&w=500&q=80" alt="Rolex Watch">
        <h3>Rolex Submariner</h3>
        <p>Luxury diving watch with classic design.</p>
        <p class="price">$9,500</p>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>
      <div class="product-card">
        <img src="pexels-ferarcosn-190819.jpg" alt="Omega Watch">
        <h3>Omega Speedmaster</h3>
        <p>The iconic Moonwatch with timeless elegance.</p>
        <p class="price">$7,200</p>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>
      <div class="product-card">
        <img src="pexels-jatin-anand-33853-128206.jpg" alt="Tag Heuer Watch">
        <h3>Tag Heuer Carrera</h3>
        <p>Sporty chronograph for speed enthusiasts.</p>
        <p class="price">$4,800</p>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>
      <div class="product-card">
        <img src="pexels-pixabay-277390.jpg" alt="Casio Watch">
        <h3>Casio G-Shock</h3>
        <p>Rugged digital watch for everyday adventures.</p>
        <p class="price">$250</p>
        <a href="#" class="buy-btn">Buy Now</a>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <div class="footer">
    <p>&copy; 2025 WatchStore. All Rights Reserved.</p>
  </div>

</body>
</html>

```
## OUTPUT
<img width="1918" height="948" alt="Screenshot 2025-08-16 190800" src="https://github.com/user-attachments/assets/70c76710-f343-4e2a-917a-f44962254f7b" />
<img width="1918" height="971" alt="Screenshot 2025-08-16 190811" src="https://github.com/user-attachments/assets/c15d0678-419b-41c2-ab0f-bc852262e341" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
