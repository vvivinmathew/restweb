# Ex.07 Restaurant Website
## Date:
14/12/2024
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

<!-- Save this file as index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #5cabfa;
            color: #333;
        }
        header {
            background-color: #47ff75;
            color: rgb(255, 255, 255);
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #453a3a;
        }
        nav a {
            color: rgb(79, 87, 247);
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #47ff81;
        }
        .banner {
            background-color:#4dff47;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: rgb(127, 158, 238);
            font-size: 2em;
            text-shadow: 2px 2px 4px #000;
        }
        .content {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: rgb(137, 167, 248);
            text-align: center;
            padding: 10px;
            position: relative;
        }
    </style>
</head>
<body>
    <header>
        <h1>viko hotel</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="banner">
        WELCOME TO viko hotel
    </div>
    <div class="content">
        <h2>About Us</h2>
        <p>! We offer variety of delicious food !</p>
    </div>
    <footer>
        <p>&copy; 2024 restaurant</p>
    </footer>
</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Home</title>
    <style>
        /* Basic Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f19494;
        }

        header {
            background-color: #61ff93;
            color: rgb(242, 160, 160);
            text-align: center;
            padding: 20px;
        }

        h1 {
            margin: 0;
        }

        .intro {
            text-align: center;
            margin-top: 20px;
        }

        .intro p {
            font-size: 1.2em;
            color: #555;
        }

        .gallery {
            display: flex;
            justify-content: space-around;
            margin: 20px;
            flex-wrap: wrap;
        }

        .gallery img {
            width: 250px;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
            margin: 10px;
        }

        footer {
            background-color: #333;
            color: rgb(235, 96, 96);
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>viko hotel</h1>
        <p>Delicious Food, nature friendly</p>
    </header>

    <div class="intro">
        <h2>speciality</h2>
        <p>Take a keen look!</p>
    </div>

    <div class="gallery">
        <!-- Image 1 -->
        <img src="biriyani.jpg" alt="POT BIRIYANI">
        <!-- Image 2 -->
        <img src="berry milk shake.jpg" alt="BERRY MILKSHAKE">
        <!-- Image 3 -->
        <img src="bread omelette.jpg" alt="BREAD OMELETTE">

    </div>

    <footer>
        <p>Designed by VIVIN MATHEW</p>
    </footer>

</body>
</html

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOTEL Menu</title>
    <style>
        /* Simple Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #61ff76;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
        }

        h2 {
            color: #6eff61;
            text-align: center;
        }

        .menu-item {
            display: flex;
            align-items: center;
            margin-bottom:-10px;
            padding: -10px;
            border-bottom: 1px solid #ddd;
        }

        .menu-item:last-child {
            border-bottom: none;
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            margin-right: 20px;
            border-radius: 8px;
        }

        .menu-item h3 {
            margin: 0;
            color: #333;
        }

        .menu-item p {
            margin: 2px;
            color: #777;
        }

        .price {
            font-weight: bold;
            color: #61ff71;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>VIKO HOTEL- Menu</h1>
    </header>

    <section>
        <h2>Our DISHES</h2>
        
        <div class="menu-item">
            <img src="noodles.jpg" alt="CHICKEN NOODLES">
            <div>
                <h3>Chicken noodles</h3>
                <p>Classic chinese chicken noodles with tomato & chilli sauce</p>
                <span class="price">Rs.120</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="fried rice.jpg" alt="FRIED RICE">
            <div>
                <h3>FRIED RICE</h3>
                <p> FLAVOURED</p>
                <span class="price">Rs.120</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="chilli chicken.jpg" alt="CHILLI CHICKEN">
            <div>
                <h3>CHILLI CHEN</h3>
                <p>Spicy AND JUICY CHILLI CHICKEN </p>
                <span class="price">Rs.150 </span>
            </div>
        </div>

        <div class="menu-item">
            <img src="parotta.jpg" alt="PAROTTA">
            <div>
                <h3>PAROTTA</h3>
                <p>SOFT AND HOT PAROTTA</p>
                <span class="price">Rs.150</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="mandi.jpg" alt="MANDI BIRIYANI">
            <div>
                <h3>MANDI BIRIYANI </h3>
                <p>SEASONED AND FLAVOURED MANDI</p>
                <span class="price">Rs.200</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="kothu.jpg" alt="KOTHU PAROTTA">
            <div>
                <h3>KOTHU PAROTTA </h3>
                <p>CHOPPED AND BEATEN WELL</p>
                <span class="price">Rs.200</span>
            </div>
        </div>
        
        <div class="menu-item">
            <img src="sandwich.jpg" alt="SANDWICH">
            <div>
                <h3>SANDWICH </h3>
                <p>SOFT AT EVERY BITE</p>
                <span class="price">Rs.90</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="grill.jpg" alt="GRILL(FULL)">
            <div>
                <h3>GRILL(FULL)</h3>
                <p>JUICY SOFT</p>
                <span class="price">Rs.500</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="pizza.jpg" alt="PIZZA">
            <div>
                <h3>PIZZA </h3>
                <p></p>
                <span class="price">Rs.200</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="dosa.jpg" alt="DOSA">
            <div>
                <h3>DOSA</h3>
                <p>SOFT AND THIN</p>
                <span class="price">Rs.20</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="burger.jpg" alt="BURGER">
            <div>
                <h3>BURGER </h3>
                <p>STUFFED WITH CHEESE AND CHICKEN</p>
                <span class="price">Rs.150</span>
            </div>
        </div>I

        <div class="menu-item">
            <img src="tea.jpg" alt="TEA">
            <div>
                <h3>TEA </h3>
                <p>HOT AND SWEET</p>
                <span class="price">Rs.20</span>
            </div>
        </div>
    </section>

   

</body>
</html>

admin.html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOTEL Administration</title>
    <style>
        /* Basic Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #fd2e2e;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #61ff93;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h2 {
            text-align: center;
            color: #333;
        }

        .admin-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .admin-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            width: 200px;
            text-align: center;
            margin: 10px;
        }

        .admin-item img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        .admin-item h3 {
            margin: 0;
            color: #333;
        }

        .admin-item p {
            color: #777;
            margin: 5px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>HOTEL Administration</h1>
    </header>

    <section>
        <h2>MEMBERS</h2>

        <div class="admin-list">
            <!-- Admin 1 -->
            <div class="admin-item">
                <img src="founder.jpg" alt="kali">
                <h3>kali</h3>
                <p>Founder</p>
            </div>

            <!-- Admin 2 -->
            <div class="admin-item">
                <img src="manager.jpg" alt="joseph">
                <h3>joseph</h3>
                <p>MANAGER</p>
            </div>

            <!-- Admin 3 -->
            <div class="admin-item">
                <img src="chief.jpg" alt="ambani">
                <h3>ambani</h3>
                <p> HEAD CHIEF</p>
            </div>

            <!-- Admin 4 -->
            <div class="admin-item">
                <img src="chief2.jpg" alt="kulali">
                <h3>kulali</h3>
                <p>CHIEF</p>
            </div>

            <!-- Admin 5 -->
            <div class="admin-item">
                <img src="waiter.jpg" alt="kalpana">
                <h3>kalpana</h3>
                <p>WAITER</p>
            </div>

           
        </div>

    </section>

    

</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - HOTEL</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #3fe0f6;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #64ff61;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 30px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
        }

        p {
            font-size: 1.1em;
        }

        .contact-info {
            margin-top: 20px;
        }

        .contact-info p {
            margin: 10px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-info h3 {
            margin-bottom: 15px;
            color: #66ff61;
        }

        a {
            text-decoration: none;
            color: #61ff6e;
        }
    </style>
</head>
<body>

    <header>
        <h1>VIKO HOTEL-CONTACT</h1>
    </header>

    <section>
        <h2>STAY TUNED</h2>
        <p>FOR FURTHER DETAILS VERIFY BELOW</p>

        <div class="contact-info">
            <h3>Restaurant Details:</h3>
            <p><strong>Address:</strong> NO.6/105A  GHANDI STREET ,ADAYAR AVENUE , CHENNAI</p>
            <p><strong>Phone:</strong> 9876543210,7890654321</p>
            <p><strong>Email:</strong> <a href="mailto:contact@restaurant.com">contact@viko hotel.com</a></p>
        </div>

        <h3>Business Hours:</h3>
        Monday - Friday : 24hrs
        Saturday and Sunday: leave

```

## OUTPUT:
![alt text](<vivin/restapp/static/Screenshot 2024-12-17 160755.png>)
![alt text](<vivin/restapp/static/Screenshot 2024-12-17 160937.png>)
![alt text](<vivin/restapp/static/Screenshot 2024-12-17 160951.png>)
![alt text](<vivin/restapp/static/Screenshot 2024-12-17 161027.png>)
![alt text](<vivin/restapp/static/Screenshot 2024-12-17 161109.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
