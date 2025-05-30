# Project Responsive Web Design using Bootstrap
## Date:19/05/2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dribble</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Dribble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#products">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="bg-light py-5 text-center">
    <div class="container">
      <h1>Welcome to Dribble</h1>
      <p>Your one-stop shop for all your needs.</p>
      <a href="#products" class="btn btn-primary">Shop Now</a>
    </div>
  </div>
  <!-- About Section -->
  <section id="about" class="py-5 bg-light">
    <div class="container">
      <h2 class="text-center mb-4">About Us</h2>
      <p>Dribble is dedicated to providing you with the best shopping experience. With a wide range of products and unbeatable customer service, we strive to be your favorite online store.</p>
    </div>
  </section>

  <!-- Products Section -->
  <section id="products" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Our Products</h2>
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <img src="Iphone.jpg" class="card-img-top" alt="Product 1">
            <div class="card-body">
              <h5 class="card-title">iPhone 16</h5>
              <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="Mac.jpg" class="card-img-top" alt="Product 2">
            <div class="card-body">
              <h5 class="card-title">Macbook Air</h5>
              <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <img src="Airpod.jpg" class="card-img-top" alt="Product 3">
            <div class="card-body">
              <h5 class="card-title">Airpods</h5>
              <a href="#" class="btn btn-primary">Add to Cart</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


 
  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <p class="mb-0">Designed By SHARON CLARA A</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<WhatsApp Image 2025-05-19 at 19.29.02_ba6d709c.jpg>)
![alt text](<WhatsApp Image 2025-05-19 at 19.29.25_cb56e9d1.jpg>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
