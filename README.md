# Ex.07 Restaurant Website
## Date:14.10.2025

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
restweb.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>VASHMITHA RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #0fdbf2;
            color: #d02dd0;
        }
        header {
            background-color: #e80b0b;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color: #0569ab;
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
            color: #8915ee;
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
            background-color: #a710bf;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(208, 5, 177, 0.1);
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
            color: #905e3f;
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
  <h1>VASHMITHA RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="About" class="About">
        <h1>Welcome to vashmitha Restaurant</h1>
        <p>our staffs</p>
        </section>
 <img src="I.jpg"height="200",width="200"style>
<img src="h1.jpg"height="200",width="200"style>
 <img src="h2.jpg"height="200",width="200"style>
 <img src="h3.jpg"height="200",width="200"style>
 <img src="h4.jpg"height="200",width="200"style>
 



 <footer>

  <p>© 2025 Designed By vashmitha</p>
</footer>
</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>VASHMITHA RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #fff8f0;
            color: #291515;
        }
        header {
            background-color: #d84242;
            color: rgb(71, 39, 39);
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
            color: #0ccc82;
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
            box-shadow: 0 4px 6px rgba(160, 45, 45, 0.1);
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
            color: #865b40;
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
  <h1>VASHMITHA RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="Menu" class="Menu">
        <h1>Welcome to vashmitha Restaurant</h1>
        <p>Experience the best flavors of traditional and modern cuisine in a warm and welcoming atmosphere.</p>
    </section>
 <img src="f1.jpg"height="150",width="150"stylye>
 <img src="f2.jpg3"height="150",width="150"style>
 <img src="f3.jpg"height="150",width="150"style>
 <img src="f4.jpg"height="150",width="150"style>
 <img src="f5.jpg"height="150",width="150"style>
 <img src="f6.jpg"height="150",width="150"style>
 <img src="f7.jpg"height="150",width="150"style>
 <img src="f8.jpg"height="150",width="150"style>
 



 <footer>

  <p>© 2025 Designed By Hemavarshini</p>
</footer>
</body>
</html>

contect.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Contact</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Vashmitha Restaurant</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="contact">
  <h2>Contact Us</h2>
  <p>📍 no.143 velalar street, Ranipet</p>
  <p>📞 ‪+91 8796576017‬</p>
  <p>📧 EMAIL : vash2013@gmail.com</p>
</section>

<footer>
  <p>© 2025 Vashmitha Restaurant</p>
</footer>
</body>
</html>

booking.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>VASHMITHA RESTAURANT - Book Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: pink;
      color: #ced40e;
    }
    header {
      background-color: blue;
      color: rgb(245, 248, 250);
      padding: 20px 0;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
    }
    nav {
      background-color: skyblue;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 12px 0;
    }
    nav a {
      color: black;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1em;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .booking-form {
      max-width: 600px;
      margin: 40px auto;
      background-color: rgb(58, 225, 12);
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(5, 187, 136, 0.1);
    }
    .booking-form h2 {
      text-align: center;
      color: rgb(15, 181, 203);
      margin-bottom: 25px;
      font-size: 2em;
    }
    .booking-form label {
      display: block;
      margin-bottom: 8px;
      font-weight: 600;
    }
    .booking-form input, 
    .booking-form select, 
    .booking-form textarea {
      width: 100%;
      padding: 5px;
      margin-bottom: 10px;
      border-radius: 6px;
      border: 1px solid #1207b4;
      font-size: 1em;
    }
    .booking-form button {
      background-color: rgb(171, 8, 8);
      color: rgb(224, 118, 118);
      padding: 12px 20px;
      border: none;
      border-radius: 6px;
      font-size: 1.1em;
      cursor: pointer;
      width: 100%;
    }
    .booking-form button:hover {
      background-color: rgb(236, 31, 205);
    }
    footer {
      background-color: yellowgreen;
      color: black;
      text-align: center;
      padding: 12px 10px;
      margin-top: 5px;
    }
  </style>
</head>
<body>
  <header>
    vashmitha RESTAURANT
    <nav>
      <a href="home.html">Home</a>
      <a href="about.html">About</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
      <a href="booking.html">Book Table</a>
    </nav>
  </header>

  <section class="booking-form">
    <h2>Book a Table</h2>
    <form action="#" method="POST">
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" placeholder="Your name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Your Email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" required>

      <label for="guests">Number of Guests</label>
      <input type="number" id="guests" name="guests" min="1" placeholder="Number of Guests" required>

      <label for="date">Date</label>
      <input type="date" id="date" name="date" required>

      <label for="time">Time</label>
      <input type="time" id="time" name="time" required>

      <button type="submit">Book Now</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Designed By vashmitha-25015828</p>
  </footer>
</body>
</html>

admin.html
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
    <li>dosa</li>
    <li>meals</li>
    <li>panipoori</li>
    <li>prawn</li>
    <li>sandwich</li>
    <li>butter Chicken</li>
    <li>chickenwing</li>
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
    <li>Tamil - Waitress</li>
    <li>Mithra - Manager</li>
  </ul>
</section>

<footer>
  <p>© 2025 Vashmitha Restaurant</p>
</footer>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (57).png>)
![alt text](<Screenshot (58).png>)
![alt text](<Screenshot (59).png>)
![alt text](<Screenshot (60).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
