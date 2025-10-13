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
  <meta charset="UTF-8">
  <title>VISHAL RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fff8f0;
            color: #291515;
        }
        header {
            background-color: #b02525;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color: #807240;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 12px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
                .menu {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .menu h2 {
            text-align: center;
            color: #5e3a22;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .menu-item {
            background-color: #81664c;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            border-radius: 6px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            margin-bottom: 8px;
            color: #201813;
        }
        .menu-item p {
            font-size: 1em;
            color: #5a2e00;
        }
        footer {
            background-color: #9a0707;
            color: white;
            text-align: center;
            padding: 18px 10px;
            margin-top: 40px;
        }
    </style>    

</head>
<body>
<header>
  <h1>VISHAL RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="Home" class="Home">
        <h1>Welcome to vishal Restaurant</h1>
        <p>Experience the best flavors of traditional and modern cuisine in a warm and welcoming atmosphere.</p>
    </section>
 <img src=" "height="700",width="700"style="display: block; margin: 0 auto;">
<footer>
  <p>© 2025 Designed By vishal/p>
</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>VISHAL RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fff8f0;
            color: #291515;
        }
        header {
            background-color: #8d5f5f;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color: #625b40;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 12px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
                .menu {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .menu h2 {
            text-align: center;
            color: #83624c;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .menu-item {
            background-color: #81664c;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            border-radius: 6px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            margin-bottom: 8px;
            color: #201813;
        }
        .menu-item p {
            font-size: 1em;
            color: #5a2e00;
        }
        footer {
            background-color: #8e2929;
            color: white;
            text-align: center;
            padding: 18px 10px;
            margin-top: 40px;
        }
    </style>    

</head>
<body>
<header>
  <h1>VISHAL  RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="Menu" class="Menu">
        <h1>Welcome to VISHAL Restaurant</h1>
        <p>Experience the best flavors of traditional and modern cuisine in a warm and welcoming atmosphere.</p>
    </section>
 <img src="food1.jpg"height="700",width="700"style="display: block; margin: 0 auto;">
<img src="food2.jpg"height="700",width="700"style="display: block; margin: 0 auto;">
 <img src="food3.jpg"height="700",width="700"style="display: block; margin: 0 auto;">
 <img src="food4.webp"height="700",width="700"style="display: block; margin: 0 auto;">
 <img src="food5.webp"height="700",width="700"style="display: block; margin: 0 auto;">




 <footer>

  <p>© 2025 Designed By vishal</p>
</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Dashboard</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Admin Dashboard</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Logout</a>
  </nav>
</header>

<section class="dashboard">
  <h2>Available Dishes</h2>
  <ul>
    <li>burger</li>
    <li>corndog</li>
    <li>momos </li>
    <li>pancake</li>
    <li>Chicken Biryani</li>
,  </ul>

  <h2>Add New Dish</h2>
  <form>
    <input type="text" placeholder="Dish Name">
    <input type="text" placeholder="Price">
    <button type="submit">Add Dish</button>
  </form>

  <h2>Employees on Shift</h2>
  <ul>
    <li>kiran- Chef</li>
    <li>Sanjana- Waitress</li>
    <li>Mithra - Manager</li>
  </ul>
</section>

<footer>
  <p>© 2025 VISHAL Restaurant</p>
</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Contact</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>vishal Restaurant</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="contact">
  <h2>Contact Us</h2>
  <p>📍 no.143 kalaingnar street, tuticorin</p>
  <p>📞 ‪+91 9790829517‬</p>
  <p>📧 EMAIL : vishalpavan2007@gmail.com</p>
</section>

<footer>
  <p>© 2025 VISHAL Restaurant</p>
</footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>VISHAL RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fff8f0;
            color: #291515;
        }
        header {
            background-color: #8d5f5f;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color: #625b40;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 12px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
                .menu {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .menu h2 {
            text-align: center;
            color: #83624c;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .menu-item {
            background-color: #81664c;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            border-radius: 6px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            margin-bottom: 8px;
            color: #201813;
        }
        .menu-item p {
            font-size: 1em;
            color: #5a2e00;
        }
        footer {
            background-color: #8e2929;
            color: white;
            text-align: center;
            padding: 18px 10px;
            margin-top: 40px;
        }
    </style>    

</head>
<body>
<header>
  <h1>VISHAL RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="About" class="About">
        <h1>Welcome to  Restaurant</h1>
        <p>our staffs</p>
        </section>
 <img src="m1.webp"height="700",width="700"style="display: block; margin: 0 auto;">
<img src="m2.webp"height="700",width="700"style="display: block; margin: 0 auto;">
 <img src="m3.webp"height="700",width="700"style="display: block; margin: 0 auto;">
 




 <footer>

  <p>© 2025 Designed By Vishal</p>
</footer>
</body>
</html>>
```

# OUTPUT:
![banner png](https://github.com/user-attachments/assets/39c9df98-6a50-453f-942c-bee8db5023b5)
![vishal rest](https://github.com/user-attachments/assets/f5ab97e2-0672-44b9-90ee-d89448ae6bb2)
![vis](https://github.com/user-attachments/assets/ca561ba5-13f5-42d8-947b-fefc1267ccf1)







# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
