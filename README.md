# Ex.06 Restaurant Website
## Date:28-12-2025  

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
    <title>HOMEPAGE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>KL CAFE</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="home">      
        <h1>Welcome to KL CAFE</h1>
        <p>Where trend meets tradition</p>
    </section>
     <section id="story"class="story">
            
        </section>
    <footer>
        <p>&copy; 2025 KL CAFE. All Rights Reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        
    <h1>KL CAFE </h1`>
        
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="menu" class="story">
        <h2>Today's Special</h2>
        <div class="menu">
            <div class="items">
                <h3>Plate Shawarma</h3>
                <img src="download (1).jpeg" alt="Shawarma" align="center">
                
            </div>
            <div class="items">
                <h3>Double Burger</h3>
                <img src="download (2).jpeg" alt="Burger" align="center">
                
            </div>
            <div class="items">
                <h3>Tandoori</h3>
                <img src="download (3).jpeg" alt="Tandoori" align="center">
                
            </div>
            
            
        
    </section>
    <footer>
        <p>&copy; 2025 KL Cafe. All Rights Reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - KL CAFE</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
       <h1>KL CAFE</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>Staff Members</h2>
        <div class="menu">
            <div class="staff">
                <img src="download (4).jpeg" alt="ANIL SHARMA - Head Chef" style="width:200px;height:auto;">
                <h3>ANIL</h3>
            </div>
            <div class="staff">
                <img src="images (1).jpeg" alt="Steven - Assistant Chef" style="width:200px;height:auto;">
                <h3>Steven</h3>
            </div>
            <div class="staff">
                <img src="images.jpeg" alt="Mike Tyson - Restaurant Manager" style="width:200px;height:auto;">
                <h3>Mike Tyson</h3>
            </div>
            
        
    </section>
    <footer>
        <p>&copy; 2025 KL CAFE. All Rights Reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
     <header>
        <h1>KL Cafe</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="contact" class="story">
             <h2>People's all time Service</h2>
            <p>We are located at Poonamalee,Chennai.</p>
            <p><strong>Phone:</strong>9856877896</p>
            <p><strong>Email:</strong> www.klcafe@gmail.com</p>
            <br>
            <p><strong>Hours:</strong></p>
            <p> 7:00 AM - 11:30 PM</p>
            
    </section>
    <footer>
        <p>&copy; 2025 KL CAFE. All Rights Reserved.</p>
    </footer>
</body>
</html

body{
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #000000;
        }
        header{
            background-color: #000000;
            color: #d60000;
            font-family: 'brush script mt', cursive;
            font-size: 1.2em;
            padding: 0.1em 2em;
            display: flex;
            position: sticky;
            justify-content: space-between;
            align-items: center;     
        }
        nav ul{
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 2rem;
        }
        nav a{
            color: #d60000;
            text-decoration: none;
            font-size: 1.5em;
        }
        .home{
            background: url('download (5).jpeg') center/cover no-repeat;
            height: 100vh;
            padding: 0.1em 0em;
            text-align: center;
            align-content: center;
            color:#ffffff;
            font-size: 2em;
            font-family:'Playfair Display', serif;
            font-style:italic;
            text-shadow: 2px 2px 6px #000;
        }
        section{
            text-align: center;
            font-size: 1.5em;
            font-family: 'Playfair Display', serif;
            font-style: bold;
            padding: 2em;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 2em;
        }
        .items {
            background-color: #fb8818;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.815);
            padding: 1em;
            width: 250px;
        }
        .items img{
            width: 100%;
            border-radius: 10px;
        }
        .story{
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
        }
        .staff{
            background-color: #9f9e9e;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.815);
            padding: 1em;
            width: 250px;
        }
        footer {
        background-color: #000000;
        color: #d60000;
        text-align: center;
        padding: 0.5em;
        }

```

## OUTPUT:
![alt text](<Screenshot 2025-12-28 232212.png>)
![alt text](<Screenshot 2025-12-28 232228.png>)
![alt text](<Screenshot 2025-12-28 232243.png>)
![alt text](<Screenshot 2025-12-28 232258.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
