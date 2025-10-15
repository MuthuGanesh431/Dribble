# Project Responsive Web Design using Bootstrap
## Date:15.10.2025

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LEGO</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<head>
    <style>
        body {
            background-color: #f0f0f0; /* Sets a light gray background color */
            background-image: url("Scene-The-LEGO-Movie.webp"); /* Sets a background image */
            background-repeat: no-repeat; /* Prevents the image from repeating */
            background-size: cover; /* Stretches the image to cover the entire page */
        }
    </style>
</head>
<body>

    <!----Navbar-->
    <nav class="navbar navbar-expand-lg navbar-dark" id="navbar">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">LEGO</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mx-auto">
        <li class="nav-item">
          <a class="nav-link active"  href="#home">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active"  href="#shopping">Shopping</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active"  href="#profile">Profile</a>
        </li>
        
        </ul>
        <button class="btn p-2 my-lg-0 my-2"> Sign in</button>
      </form>
    </div>
  </div>
</nav>




<section id="home">
    <h1 class="text-center">LEGO TOYS</h1>
    <div class="input-group m-4">
        <input type="text" class="form-control" placeholder="Email Address">

            <button class="btn signin">Get Started</button>
    </div>
</section>

<!-----Shopping-->

<head>
    <style>
        body {
            background-color: #f0f0f0; /* Sets a light gray background color */
            background-image: url("Worlds_Mainstage-Picsart-AiImageEnhancer.jpeg"); /* Sets a background image */
            background-repeat: no-repeat; /* Prevents the image from repeating */
            background-size: cover; /* Stretches the image to cover the entire page */
        }
    </style>
</head>

<section id="shopping"> 
    <div class="container-fluid">
      <div class="row">
       <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LEGO Shop</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #ffcc00;
            color: #333;
            padding: 1em 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        .container {
            width: 80%;
            margin: 2em auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .product-card {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1em;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .product-card img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .product-card h3 {
            margin: 0.5em 0;
            font-size: 1.2em;
        }

        .product-card .price {
            color: #e60000;
            font-size: 1.5em;
            font-weight: bold;
            margin: 0.5em 0;
        }

        .product-card button {
            background-color: #337ab7;
            color: #fff;
            border: none;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            display: inline-block;
            font-size: 16px;
            margin-top: 10px;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .product-card button:hover {
            background-color: #286090;
        }
    </style>
</head>
<body>

    <header>
        <h1>LEGO Shop</h1>
    </header>

    <div class="container">
        <div class="product-card">
            <img src="fire truck.jpg" alt="LEGO City Fire Truck">
            <h3>LEGO City Fire Truck</h3>
            <p>A classic fire truck for your LEGO city.</p>
            <div class="price">Rs.2000</div>
            <button>Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="star wars.jpg" alt="LEGO Star Wars X-Wing">
            <h3>LEGO Star Wars X-Wing</h3>
            <p>Recreate epic battles with this iconic starfighter.</p>
            <div class="price">Rs.5000</div>
            <button>Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="lego creater.png" alt="LEGO Creator 3-in-1">
            <h3>LEGO Creator 3-in-1</h3>
            <p>Build a jet, a helicopter, or a speedboat.</p>
            <div class="price">Rs.3000</div>
            <button>Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="bugatti.jpg" alt="LEGO Technic Bugatti">
            <h3>LEGO Technic Bugatti</h3>
            <p>An advanced build for true car enthusiasts.</p>
            <div class="price">Rs.800</div>
            <button>Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="tree house.webp" alt="LEGO Friends Tree House">
            <h3>LEGO Friends Tree House</h3>
            <p>A fun and colorful treehouse set.</p>
            <div class="price">Rs.1500</div>
            <button>Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="avengers.jpg" alt="LEGO Marvel Avengers Tower">
            <h3>LEGO Marvel Avengers Tower</h3>
            <p>Assemble the heroes at the iconic tower.</p>
            <div class="price">Rs.10000</div>
            <button>Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="creeper.jpg" alt="LEGO Minecraft The Creeper">
            <h3>LEGO Minecraft The Creeper</h3>
            <p>Step into the world of Minecraft with this set.</p>
            <div class="price">Rs.10000</div>
            <button>Add to Cart</button>
        </div>

        <div class="product-card">
            <img src="ship.jpg" alt="LEGO Ideas Ship in a Bottle">
            <h3>LEGO Ideas Ship in a Bottle</h3>
            <p>A beautiful and intricate display piece.</p>
            <div class="price">Rs.2500</div>
            <button>Add to Cart</button>
        </div>
         <div class="product-card">
            <img src="dc.png" alt="LEGO DC">
            <h3>LEGO DC</h3>
            <p>I am Batman!.</p>
            <div class="price">Rs.8000</div>
            <button>Add to Cart</button>

    </div>
     <div class="product-card">
            <img src="harry porter.png" alt="LEGO Harry Porter">
            <h3>LEGO Harry Porter</h3>
            <p>Let's go journey to hogwards.</p>
            <div class="price">Rs.15000</div>
            <button>Add to Cart</button>
     </div>

</body>
</html>

        </div>
      </div>
    </div>
</section>
<!-----Profile-->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Profile | LEGO Store</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: #f9fafb;
      color: #333;
    }

    header {
      background-color: #ffcf00;
      color: #222;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    header h1 {
      font-size: 24px;
      font-weight: 700;
      letter-spacing: 1px;
    }

    header a {
      text-decoration: none;
      color: #222;
      font-weight: 600;
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      background: white;
      border-radius: 15px;
      padding: 30px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    .profile-header {
      display: flex;
      align-items: center;
      gap: 20px;
    }

    .profile-header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid #ffcf00;
      object-fit: cover;
    }

    .profile-header h2 {
      margin: 0;
      font-size: 24px;
      color: #333;
    }

    .info {
      margin-top: 30px;
    }

    .info h3 {
      border-left: 5px solid #ffcf00;
      padding-left: 10px;
      color: #222;
      font-size: 20px;
    }

    .info p {
      margin: 10px 0;
      font-size: 16px;
    }

    .orders, .wishlist {
      margin-top: 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 15px;
    }

    .card {
      background: #fefefe;
      border-radius: 12px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.08);
      transition: transform 0.2s;
    }

    .card:hover {
      transform: translateY(-4px);
    }

    .card img {
      width: 100%;
      height: 160px;
      object-fit: contain;
      margin-bottom: 10px;
    }

    .card h4 {
      font-size: 16px;
      margin: 0;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      padding: 20px;
      color: #666;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>LEGO Store</h1>
    <a href="#">Logout</a>
  </header>

  <div class="container">
    <div class="profile-header">
      <img src="profile.jpg" alt="User Profile">
      <div>
        <h2>Muthu Ganesh</h2>
        <p>LEGO Builder Level: Master Creator 🧱</p>
      </div>
    </div>

    <div class="info">
      <h3>Account Info</h3>
      <p><strong>Email:</strong> muthu@example.com</p>
      <p><strong>Address:</strong> 45, Brick Street, Chennai, India</p>
      <p><strong>Member Since:</strong> March 2024</p>
    </div>

    <div class="info">
      <h3>My Orders</h3>
      <div class="orders">
        <div class="card">
          <img src="lego creater.png" alt="LEGO Set">
          <h4>Bookshop Creator Expert</h4>
        </div>
        <div class="card">
          <img src="star wars.jpg" alt="LEGO Star Wars">
          <h4>Star Wars TIE Fighter</h4>
        </div>
      </div>
    </div>

    <div class="info">
      <h3>Wishlist</h3>
      <div class="wishlist">
        <div class="card">
          <img src="tree house.webp" alt="LEGO Tree House">
          <h4>Tree House Set</h4>
        </div>
        <div class="card">
          <img src="ship.jpg" alt="LEGO Pirate Ship">
          <h4>Pirate Ship Set</h4>
        </div>
      </div>
    </div>
  </div>

  <footer>
    © 2025 LEGO Store | Built with ❤️ by MG
  </footer>
</body>
</html>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.min.js"></script>
    

</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-10-15 215416.png>)
![alt text](<Screenshot 2025-10-15 215436.png>)
![alt text](<Screenshot 2025-10-15 215504.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
