<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Furni. | Responsive Furniture Website</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light" style="background-color: cadetblue;">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="Screenshot 2024-12-22 4.45.20 PM.png" alt="Logo" class="img-fluid" style="height: 80px;">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item"><a class="nav-link text-white" href="#">Home</a></li>
            <li class="nav-item"><a class="nav-link text-white" href="#">About</a></li>
            <li class="nav-item"><a class="nav-link text-white" href="#">Contact</a></li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle text-white" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown">Furniture</a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Beds</a></li>
                <li><a class="dropdown-item" href="#">Sofas</a></li>
                <li><a class="dropdown-item" href="#">Chairs & Tables</a></li>
                <li><a class="dropdown-item" href="#">Decorations</a></li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Carousel -->
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="pexels-arina-krasnikova-5712530.jpg" class="d-block w-100 img-fluid" alt="Slide 1">
          <div class="carousel-caption">
            <h4>Stylish & Durable Furniture for Every Home</h4>
            <p>Crafted to last a lifetime with premium materials.</p>
            <button type="button" class="btn btn-outline-light">Shop Now</button>
          </div>
        </div>
        <!-- Add more carousel items if needed -->
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon"></span>
      </button>
    </div>

    <!-- Product Section -->
    <div class="container my-5">
      <h3 class="text-center">Featured Products</h3>
      <div class="row g-4">
        <div class="col-12 col-md-4">
          <div class="card h-100">
            <img src="pexels-arina-krasnikova-5712530.jpg" class="card-img-top img-fluid" alt="Product 1">
            <div class="card-body">
              <h5 class="card-title">Four Seats Dining Table</h5>
              <p><s class="text-danger">$60.99</s> $50.99</p>
              <a href="#" class="btn btn-dark">Add to Cart</a>
            </div>
          </div>
        </div>
        <!-- Add more product cards -->
      </div>
    </div>

    <!-- Blog Section -->
    <div class="container my-5">
      <h3 class="text-center">Blog</h3>
      <div class="row g-4">
        <div class="col-12 col-md-6">
          <div class="card">
            <div class="row g-0">
              <div class="col-md-4">
                <img src="image1.jpg" class="img-fluid rounded-start" alt="Blog Image 1">
              </div>
              <div class="col-md-8">
                <div class="card-body">
                  <h5 class="card-title">Why Durable Furniture Matters</h5>
                  <p>Investing in durable furniture saves money and ensures a sustainable lifestyle.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Add more blog cards -->
      </div>
    </div>

    <!-- Footer -->
    <footer class="text-center py-4" style="background-color: cadetblue; color: white;">
      <div class="container">
        <ul class="nav justify-content-center border-bottom pb-3 mb-3">
          <li class="nav-item"><a href="#" class="nav-link px-2 text-light">Home</a></li>
          <li class="nav-item"><a href="#" class="nav-link px-2 text-light">About</a></li>
          <li class="nav-item"><a href="#" class="nav-link px-2 text-light">Contact</a></li>
          <li class="nav-item"><a href="#" class="nav-link px-2 text-light">Furniture</a></li>
        </ul>
        <p>© 2024 Company, Inc.</p>
      </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>
