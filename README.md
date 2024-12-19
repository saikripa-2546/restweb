# Ex.07 Restaurant Website
## Date:

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
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Family Diner</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <div class="banner-content">
            <h1>Welcome to Our Restaurant</h1>
            <p>We serve the finest dishes made with fresh ingredients. Come visit us!</p>
        </div>
    </section>

    <footer>
        <p>Designed by [saikripa]</p>
    </footer>
</body>
</html>

administration.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Chefs - Little Lemon Restaurant</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="home.html">Menu</a></li>
        <li><a href="chefs.html">Our Chefs</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="chefs">
    <h2>Meet Our Chefs</h2>
    <div class="chef">
      <img src="chef1.png" alt="Chef 1">
      <h3>Chef srisha</h3>
      <p>Specializes in Italian cuisine and fresh pasta dishes.</p>
    </div>
    <div class="chef">
      <img src="chef2.png" alt="Chef 2">
      <h3>Chef sandhiya</h3>
      <p>Expert in Indian cuisine and plant-based cooking.</p>
    </div>
    <div class="chef">
      <img src="chef3.png" alt="Chef 2">
      <h3>Chef dharshini</h3>
      <p>Expert in vegan dishes and plant-based cooking.</p>
    </div>
    <div class="chef">
      <img src="chef4.png" alt="Chef 2">
      <h3>Chef adhithya</h3>
      <p>Expert in japanese cuisine and rice-based cooking.</p>
    </div>
  </section>

</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - The Family Diner</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Our Menu</h1>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="M1.png" alt="Ramen">
                <h2>Ramen</h2>
                <p class="price">rs.400</p>
            </div>
            <div class="menu-item">
            <img src="M2.png" alt="Udon">
                <h2>Udon</h2>
                <p class="price">rs.200</p>
            </div>
            <div class="menu-item">
                <img src="M3.png" alt="Miso-soup">
                <h2>Miso-soup</h2>
                <p class="price">rs.232</p>
            </div>
            <div class="menu-item">
                <img src="M4.png" alt="Chole bhature">
                <h2>Chole bhature</h2>
                <p class="price">rs.350</p>
            </div>
            <div class="menu-item">
                <img src="M5.png" alt="Biriyani">
                <h2>Biriyani</h2>
                <p class="price">rs.555</p>
            </div>
            <div class="menu-item">
                <img src="M6.png" alt="Lasagna">
                <h2>Lasagna</h2>
                <p class="price">rs.499</p>
            </div>
        <div class="menu-item">
            <img src="M7.png" alt="Risotto">
            <h2>Risotto</h2>
            <p class="price">rs.222</p>
        </div>
        <div class="menu-item">
            <img src="M8.png" alt="Frankies">
            <h2>Frankies</h2>
            <p class="price">rs.90</p>
        </div>
        <div class="menu-item">
            <img src="M9.png" alt="Coconut rice bowl">
            <h2>Coconut rice bowl</h2>
            <p class="price">rs.100</p>
        </div>
        <div class="menu-item">
            <img src="M10.png" alt="Parotta">
            <h2>Parotta</h2>
            <p class="price">rs.70</p>
        </div>





    </section>

    <footer>
        <p>Designed by [Sai Kripa]</p>
    </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - The Family Diner</title>
    <link rel="stylesheet" href="st.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Address: 789 Restaurant St., City, Country</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@skrestaurant.com</p>
    </section>

    <footer>
        <p>Designed by [Sai Kripa]</p>
    </footer>
</body>
</html>

st.css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: white;
  padding: 10px 0;
  text-align: center;
}

header nav ul {
  list-style-type: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

section {
  padding: 20px;
  margin: 20px;
}

section h1 {
  font-size: 2em;
  color: #333;
}

section .menu ul {
  list-style-type: none;
}

section .menu li {
  margin: 15px 0;
}

section .team-member {
  display: inline-block;
  margin: 10px;
  text-align: center;
}

section .team-member img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
}

sty.css
/* General styles for the body */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
  background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
  color: white;
  padding: 10px 0;
  text-align: center;
}

header nav ul {
  list-style-type: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

/* Administration Section */
.administration {
  padding: 40px;
  text-align: center;
  background-color: #fff;
}

.administration h1 {
  font-size: 2.5em;
  margin-bottom: 40px;
  color: #333;
}

/* Grid Layout for Team Members */
.team-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 30px;
  justify-items: center;
  padding: 20px;
}

/* Individual Team Member Card */
.team-member {
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  padding: 20px;
  width: 100%;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.team-member:hover {
  transform: scale(1.05); /* Slight zoom effect */
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Team Member Image Styling */
.team-member img {
  width: 100%;
  height: 200px; /* Fixed height for uniformity */
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 15px;
}

/* Team Member Name */
.team-member h2 {
  font-size: 1.5em;
  margin: 10px 0;
  color: #333;
}

/* Team Member Designation */
.team-member p {
  font-size: 1em;
  color: #777;
  margin-top: 5px;
}

/* Footer styles */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}   

style.css
/* General styles for the body */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
  background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
  color: white;
  padding: 10px 0;
  text-align: center;
}

header nav ul {
  list-style-type: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

/* Banner section with background image */
.banner {
  background-image: url('BG\ .1.avif'); /* Change this to the path of your image */
  background-size: cover;
  background-position: center;
  height: 500px; /* Adjust the height of the banner */
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  text-align: center;
  position: relative;
}

.banner-content {
  z-index: 1; /* Makes sure the text is above the background */
}

.banner h1 {
  font-size: 3em;
  margin: 0;
}

.banner p {
  font-size: 1.2em;
}

/* Footer styles */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

/* Other sections styling */
section {
  padding: 20px;
  margin: 20px;
}

section h1 {
  font-size: 2em;
  color: #333;
}

section .menu ul {
  list-style-type: none;
}

section .menu li {
  margin: 15px 0;
}

section .team-member {
  display: inline-block;
  margin: 10px;
  text-align: center;
}

section .team-member img {
  width: 250px;
  height: 250px;
  border-radius: 50%;
}
img {
  width: 150px;
  height: 150px;
}

styles.css
/* General styles for the body */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
  background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
  color: white;
  padding: 10px 0;
  text-align: center;
}

header nav ul {
  list-style-type: none;
  padding: 0;
}

header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 18px;
}

/* Menu Section */
.menu {
  padding: 20px;
  text-align: center;
}

.menu h1 {
  font-size: 2.5em;
  margin-bottom: 20px;
  color: #333;
}

/* Grid Layout for Menu Items */
.menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
  gap: 20px;
  justify-items: center;
  padding: 20px;
}

/* Individual Menu Item Styles */
.menu-item {
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  padding: 20px;
  width: 100%;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-item:hover {
  transform: scale(1.05); /* Slight zoom effect */
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Menu Item Image */
.menu-item img {
  width: 100%;
  height: auto;
  border-radius: 10px;
}

/* Menu Item Name */
.menu-item h2 {
  font-size: 1.5em;
  margin: 15px 0;
  color: #333;
}

/* Menu Item Description */
.menu-item p {
  color: #777;
  font-size: 1em;
  margin-bottom: 10px;
}

/* Price Styling */
.menu-item .price {
  font-size: 1.2em;
  font-weight: bold;
  color: #e60000;
}

/* Footer styles */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
img {
  width: 100px;
  height: 100px;
}
```

## OUTPUT:
![alt text](<Screenshot 2024-12-19 205455.png>) 
![alt text](<Screenshot 2024-12-19 205536.png>) 
![alt text](<Screenshot 2024-12-19 205552.png>) 
![alt text](<Screenshot 2024-12-19 205622.png>) 
![alt text](<Screenshot 2024-12-19 205640.png>) 
![alt text](<Screenshot 2024-12-19 205700.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
