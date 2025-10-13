# Ex.07 Restaurant Website
# Date:13-10-2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Construction Ecommerce</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(90deg, #e0ecef 0%, #faf8f1 100%);
    }
    .sidebar {
      background: #f9f5e7;
      border-radius: 8px;
      padding: 24px;
      box-shadow: 0 4px 18px -2px #d1cfcf;
      min-height: 250px;
      margin-top: 30px;
    }
    .product-card {
      border-radius: 12px;
      box-shadow: 0 4px 14px rgba(50, 90, 130, 0.08);
      padding: 18px 14px;
      background: #fff;
      margin-bottom: 32px;
      transition: box-shadow 0.18s;
    }
    .product-card:hover {
      box-shadow: 0 8px 18px rgba(45, 88, 110, 0.18);
    }
    .product-img {
      max-width: 100%;
      border-radius: 10px;
      margin-bottom: 8px;
    }
    .badge-category {
      background: #ffe066;
      color: #554400;
      font-size: 0.85rem;
    }
    .btn-buy {
      background: linear-gradient(90deg, #ffe066 70%, #6ec6f0 100%);
      color: #3f3f3f;
      font-weight: bold;
      border: none;
    }
    .page-title {
      font-weight: bold;
      font-size: 2.2rem;
      color: #4b3bda;
      letter-spacing: 2px;
      margin: 26px 0;
    }
    footer {
      background: #4b3bda;
      color: #fff;
      text-align: center;
      padding: 16px 0 10px 0;
      border-top-left-radius: 18px;
      border-top-right-radius: 18px;
    }
  </style>
</head>
<body>
<div class="container-fluid">
  <div class="row">
    <div class="col-12 text-center">
      <h1 class="page-title">Construction Ecommerce Store</h1>
    </div>
  </div>
  <div class="row">
    <!-- Sidebar -->
    <div class="col-md-3">
      <div class="sidebar">
        <h5>Categories</h5>
        <ul class="list-group">
          <li class="list-group-item"><a href="#">Cement</a></li>
          <li class="list-group-item"><a href="#">Bricks</a></li>
          <li class="list-group-item"><a href="#">Steel</a></li>
          <li class="list-group-item"><a href="#">Paints</a></li>
          <li class="list-group-item"><a href="#">Tools</a></li>
        </ul>
        <h6 class="mt-4">Popular Brands</h6>
        <span class="badge bg-warning text-dark me-2 mb-2">UltraTech</span>
        <span class="badge bg-info text-dark me-2 mb-2">ACC</span>
        <span class="badge bg-success text-light mb-2">Tata Steel</span>
      </div>
    </div>
    <!-- Products -->
    <div class="col-md-9">
      <div class="row">
        <div class="col-lg-4 col-md-6">
          <div class="product-card text-center">
            <span class="badge badge-category mb-2">Cement</span>
            <img src="https://images.unsplash.com/photo-1556742413-6e4b8c1d94a4?auto=format&fit=crop&w=400&q=80" alt="Cement" class="product-img">
            <h5 class="mt-2">UltraTech PPC Cement</h5>
            <p class="text-muted">High strength for all projects</p>
            <h6 class="fw-bold">₹375 / bag</h6>
            <button class="btn btn-buy mt-2">Buy Now</button>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="product-card text-center">
            <span class="badge badge-category mb-2">Bricks</span>
            <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=400&q=80" alt="Bricks" class="product-img">
            <h5 class="mt-2">Red Clay Bricks</h5>
            <p class="text-muted">Durable, eco-friendly walls</p>
            <h6 class="fw-bold">₹6 / piece</h6>
            <button class="btn btn-buy mt-2">Buy Now</button>
          </div>
        </div>
        <div class="col-lg-4 col-md-6">
          <div class="product-card text-center">
            <span class="badge badge-category mb-2">Steel</span>
            <img src="https://images.unsplash.com/photo-1464983953574-0892a716854b?auto=format&fit=crop&w=400&q=80" alt="Steel" class="product-img">
            <h5 class="mt-2">Tata Steel TMT Bar</h5>
            <p class="text-muted">Strength for beams & columns</p>
            <h6 class="fw-bold">₹58 / kg</h6>
            <button class="btn btn-buy mt-2">Buy Now</button>
          </div>
        </div>
        <!-- Add more products as needed -->
      </div>
    </div>
  </div>
</div>
<footer>
  &copy; 2025 Construction Store | All rights reserved
</footer>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

# OUTPUT:

<img width="1914" height="1015" alt="vishal1" src="https://github.com/user-attachments/assets/b6cde9fb-f3b2-4ef2-b1bd-5675b4d18c9b" />
<img width="1876" height="1021" alt="vishal3" src="https://github.com/user-attachments/assets/577cf790-5e61-4ee0-bdc5-0958aa7bd2b5" />
<img width="1883" height="1024" alt="vishal4" src="https://github.com/user-attachments/assets/279d67ee-c28e-4818-b558-e9747a65bcde" />
<img width="1903" height="774" alt="vishal5" src="https://github.com/user-attachments/assets/22b9a97d-83f5-4f4a-97ae-784ca8c415e9" />










# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
