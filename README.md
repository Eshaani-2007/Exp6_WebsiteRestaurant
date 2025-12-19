# Ex.06 Restaurant Website
## Date:19.12.2025

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
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>THE COFFEE SPOT</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:#f8f4ef;       
      color:#3b2f2f;            
    }

    header{
      background:#4b2e2b;      
      padding:20px 40px;
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    header h1{
      letter-spacing:2px;
    }

    nav a{
      color:#f5e6d3;
      text-decoration:none;
      margin:0 12px;
      font-weight:bold;
    }

    nav a:hover{
      color:#d9a066;           
    }

    .hero{
      height:70vh;
      background:url('PIC8.jpg') center/cover no-repeat;
      display:flex;
      justify-content:center;
      align-items:center;
    }

    .hero h2{
      background:rgba(75,46,43,0.85);
      color:white;
      padding:18px 30px;
      border-radius:8px;
      font-size:28px;
    }

    section{
      padding:55px 40px;
    }

    h2{
      text-align:center;
      margin-bottom:30px;
      color:#4b2e2b;
      font-size:32px;
    }

    
    .about{
      display:flex;
      gap:30px;
      align-items:center;
      justify-content:center;
    }

    .about p{
      max-width:500px;
      font-size:17px;
      line-height:1.6;
    }

    .about img{
      width:100%;
      max-width:420px;
      border-radius:12px;
    }

    
    .menu{
      display:flex;
      gap:25px;
      flex-wrap:wrap;
      justify-content:center;
    }

    .menu-card{
      background:#fffaf5;
      width:260px;
      border-radius:12px;
      overflow:hidden;
      box-shadow:0 6px 15px rgba(0,0,0,0.12);
    }

    .menu-card img{
      width:100%;
      height:180px;
      object-fit:cover;
    }

    .menu-card div{
      padding:15px;
      text-align:center;
    }

    .menu-card h3{
      color:#4b2e2b;
      margin-bottom:8px;
    }

    .menu-card p{
      color:#a47148;
      font-weight:bold;
      font-size:18px;
    }

    
    .gallery{
      display:flex;
      gap:20px;
      flex-wrap:wrap;
      justify-content:center;
    }

    .gallery img{
      width:260px;
      border-radius:10px;
      box-shadow:0 5px 12px rgba(0,0,0,0.15);
    }

   
    .contact{
      background:#4b2e2b;
      color:#f5e6d3;
      text-align:center;
      padding:50px 20px;
    }

    .contact p{
      margin:8px 0;
      font-size:16px;
    }

    footer{
      background:#2e1c1a;
      color:#d2b48c;
      text-align:center;
      padding:12px;
    }

    
    @media(max-width:768px){
      .about{
        flex-direction:column;
        text-align:center;
      }

      header{
        flex-direction:column;
        gap:10px;
      }

      .hero h2{
        font-size:22px;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>THE COFFEE SPOT</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#menu">Menu</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero" id="home">
  <h2>Brewed fresh • Served with love</h2>
</div>

<section id="about">
  <h2>About Us</h2>
  <div class="about">
    <p>
      Experience rich flavors, perfect aromas, and carefully crafted coffee.
      The Coffee Spot is your everyday escape for comfort, calm, and great taste.
    </p>
    <img src="PIC7.jpg">
  </div>
</section>

<section id="menu">
  <h2>Our Menu</h2>
  <div class="menu">

    <div class="menu-card">
      <img src="PIC1.jpg">
      <div>
        <h3>Classic Cappuccino</h3>
        <p>₹280</p>
      </div>
    </div>

    <div class="menu-card">
      <img src="PIC2.jpg">
      <div>
        <h3>Cold Coffee</h3>
        <p>₹180</p>
      </div>
    </div>

    <div class="menu-card">
      <img src="PIC3.jpg">
      <div>
        <h3>Signature Hot Chocolate</h3>
        <p>₹320</p>
      </div>
    </div>

  </div>
</section>

<section id="gallery">
  <h2>Gallery</h2>
  <div class="gallery">
    <img src="PIC4.jpg">
    <img src="PIC5.jpg">
    <img src="PIC6.jpg">
  </div>
</section>

<section id="contact" class="contact">
  <h2>Contact Us</h2>
  <p>📍 Chennai, India</p>
  <p>📞 +91 98765 43210</p>
  <p>✉ thecoffeespot@email.com</p>
  <p>Eshaani S</p>
  <p>25008927</p>
</section>

<footer>
  <p>© 2025 THE COFFEE SPOT</p>
</footer>

</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 092217.png>)
![alt text](<Screenshot 2025-12-19 092156.png>)
![alt text](<Screenshot 2025-12-19 092125.png>)
![alt text](<Screenshot 2025-12-19 092105.png>)
![alt text](<Screenshot 2025-12-19 092050.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
