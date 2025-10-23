# Ex.07 Restaurant Website
## Date:23-10-25

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
home.html
<html>

<head>
  <title>Cattle Man's Ranch</title>
  <link rel="stylesheet" type="text/css" href="home.css">  
</head>
<body>

 
    <h1 class="site-title">Cattle Man's Ranch</h1>

  </div>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>

          <div class="banner">
    <h2>20% Off This Weekend</h2></div>



  <div class="container">
    <div class="column">
      <h3>Our New Menu</h3>
      <img src="pics/menu.jpg" alt="Grilled skewers">
      <p>Discover our latest dishes crafted with fresh ingredients and bold flavors.</p>
      <a href="#">See our new menu</a>
    </div>
    <div class="column">
      <h3>Book a Table</h3>
      <img src="pics/istockphoto-1397536730-612x612.jpg" alt="Person holding plate">
      <p>Reserve your spot and enjoy a delightful dining experience with us.</p>
      <a href="#">Book your table now</a>
    </div>
    <div class="column">
      <h3>Opening Hours</h3>
      <img src="pics/images.jpg" alt="Chef in kitchen">
      <p>We're open:</p>
      <ul>
        <li>Mon - Fri: 2pm - 10pm</li>
        <li>Sat: 2pm - 11pm</li>
        <li>Sun: 2pm - 9pm</li>
      </ul>
    </div>
  </div>

  <footer>
    &copy;Designed and Developed by <span>DEVESH C(25011036)</span>
  </footer>

</body>
</html>

home.css
* {
  box-sizing: inherit;
}

    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
     
    }

  
    header, footer {
      background-color: #f4f4f4;
      padding: 20px;
      text-align: center;
    }



nav {
  display: flex;
  justify-content: space-around; 
  background-color: #333;
  padding: 20px;
  position:relative;
  width: 100%;
  z-index: 1000;

}

nav a {
  color: white;
  text-decoration: none;
  font-size: 20px;
  padding: 12px 24px;
  background-color: #4CAF50; 
  border-radius: 8px;
  transition: background-color 0.3s ease;
  box-shadow: 0 4px 6px rgba(0,0,0,0.2);
}

nav a:hover {
  background-color: #45a049; 
}
   
.banner {
  width: 100%;
  height: 300px; 
  background-image: url('pics/banner.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-color: #ffe680;
  border-radius: 20px;
  overflow: hidden;
  margin: 20px auto;
  display: flex;
  align-items: center;
  justify-content: center;
}

    .main {
      flex: 1;
      padding: 20px;
    }

    .container {
      display: flex;
      justify-content: space-around;
      gap: 20px;
    }

    .column {
      width: 30%;
      background-color: #fafafa;
      padding: 15px;
      border-radius: 8px;
    }

    .column img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }

  
    footer {
      font-weight: bold;
      color: red;
      position: fixed;
      left: 0;
  bottom: 0;
  width: 100%;
    background-color: #f4f4f4;
    text-align: center;
     
    }

    footer span {
      color: blue;
    }
@import url('https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap');

.site-title {
  font-family: 'Rock Salt', cursive;
  font-size: 60px;
  color: #f02c2c; 
  text-align: center;
  margin-top: 20px;
}

menu.html
<html>
<head>
    <title>Cattle Man's Ranch->Menu</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Open+Sans&family=Playfair+Display&family=Roboto+Mono&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="menu.css">
        <h1 class="site-title">Cattle Man's Ranch</h1>
</head>
<body>
    <section class="menu-section">
        <h1>The Menu</h1>
        <div class="category">
                         <div class="menu-item">
                <img src="https://images.pexels.com/photos/2144112/pexels-photo-2144112.jpeg" alt="Tiramisu">
                <h3>Tiramisu</h3>
                <p>Rich coffee-flavored dessert with mascarpone and cocoa. $6.99</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/338713/pexels-photo-338713.jpeg" alt="Espresso">
                <h3>Espresso</h3>
                <p>Rich, bold Italian coffee. $3.99</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/1351238/pexels-photo-1351238.jpeg" alt="Lemon Sorbet">
                <h3>Lemon Sorbet</h3>
                <p>Refreshing lemon dessert with a zesty finish. $5.99</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/725990/pexels-photo-725990.jpeg" alt="Calamari">
                <h3>Calamari</h3>
                <p>Fried squid served with marinara sauce. $9.99</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/533325/pexels-photo-533325.jpeg" alt="Prosciutto e Melone">
                <h3>Prosciutto e Melone</h3>
                <p>Thinly sliced prosciutto wrapped around sweet melon. $8.49</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/1437267/pexels-photo-1437267.jpeg" alt="Margherita Pizza">
                <h3>Margherita Pizza</h3>
                <p>Classic pizza with fresh tomatoes, mozzarella, and basil. $12.99</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/2619967/pexels-photo-2619967.jpeg" alt="Spaghetti Carbonara">
                <h3>Spaghetti Carbonara</h3>
                <p>Creamy pasta with pancetta, egg, and Parmesan. $14.99</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/1487511/pexels-photo-1487511.jpeg" alt="Lasagna">
                <h3>Lasagna</h3>
                <p>Layers of pasta, meat sauce, and melted cheese. $15.99</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/2133989/pexels-photo-2133989.jpeg" alt="Fettuccine Alfredo">
                <h3>Fettuccine Alfredo</h3>
                <p>Creamy Alfredo sauce over fettuccine pasta. $13.49</p>
            </div>
            <div class="menu-item">
                <img src="https://images.pexels.com/photos/323682/pexels-photo-323682.jpeg" alt="Pesto Gnocchi">
                <h3>Pesto Gnocchi</h3>
                <p>Soft potato dumplings in a basil pesto sauce. $14.49</p>
            </div>


        </div>
    </section>
    <footer>
       &copy;Designed and Developed by <span>DEVESH C(25011036)</span>
    </footer>
</body>
</html>


menu.css

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
@import url('https://fonts.googleapis.com/css2?family=Rock+Salt&display=swap');
body {
    font-family: 'Rock Salt', cursive;
    color: #2A2D43;
}

.menu-section {
    padding: 50px;
    text-align: center;
    background-color: aqua;
}

.menu-section h1 {
    font-family: 'Playfair Display', serif;
    font-size: 2.5rem;
    color: #2A2D43;
    margin-bottom: 40px;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.2);
}

.category {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    padding: 20px;
}

.menu-item {
    background: #e2ba42;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    animation: scaleUp 1s ease-out forwards;
}

.menu-item:hover {
    transform: translateY(-10px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.menu-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    margin-bottom: 15px;
}

.menu-item h3 {
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
    color: #2A2D43;
    margin-bottom: 10px;
}

.menu-item p {
    font-family: 'Open Sans', sans-serif;
    font-size: 1rem;
    color: #555;
}

.menu-item .price {
    font-weight: bold;
    color: #941722;
    margin-top: 10px;
}

footer .social-links {
    margin-top: 10px;
}

footer .social-links a {
    margin: 0 10px;
}



#navbar {
    display: flex;
    flex-direction: column;
    position: absolute;
    top: 70px;
    right: 0;
    background-color: #ff1919;
    width: 100%;
    padding: 20px;
}

.menu-section {
    padding: 50px 20px;
}
    footer {
      font-weight: bold;
      color: red;
      position: fixed;
      left: 0;
  bottom: 0;
  width: 100%;
    background-color: #f4f4f4;
    text-align: center;
     
    }
    .site-title {
  font-family: 'Rock Salt', cursive;
  font-size: 60px;
  color: #f02c2c; 
  text-align: center;
  margin-top: 20px;
  background-color: black;
  border-radius: 10px  ;
}

admin.html
<html>

<head>

    <title>Administration</title>
    <link rel="stylesheet" href="admin.css">
</head>

<body>
    <header>
        <h1>Our Administration Team</h1>
    </header>
    <div class="parent">
        <div class="child"><img src="pics/Screenshot 2025-10-08 075829.png"><h2>CEO</h2></div>
        <div class="child"><img src="pics/images (2).jpg"><h2>Founder</h2></div>
        <div class="child"><img src="pics/images (1).jpg"><h2>Head Chef</h2></div>
        <div class="child"><img src="pics/images copy.jpg"><h2>Quality analyst</h2></div>
    </div>
     <footer>
    &copy;Designed and Developed by <span>DEVESH C(25011036)</span>
  </footer>

</body>
</html>

admin.css
    footer {
      font-weight: bold;
      color: red;
      position: fixed;
      left: 0;
  bottom: 0;
  width: 100%;
    background-color: #f4f4f4;
    text-align: center;
     
    }
*{
    padding:0px;
    margin:0px;
}
body{
    overflow: hidden;
     background: linear-gradient(135deg, #23ef0c, #ef19bd, #3e257d);
}
footer{
    background-color: #2e2e2e;
    font-family: 'Roboto Mono', monospace;
    color:#FAF9F6;
    position:fixed;
    bottom: 0%;
    
    text-align:center;
    display: block;
    width:100%;
    padding:20px;
}
header{
    background-color:#200930;
    color:white;
    text-align: center;
    text-shadow : 2px 2px 4px rgba(0,0,0,0.4);
    padding:20px;
    width:100%;
}
.parent{
    display:flex;
    flex-direction:row;
    justify-content:center;
    margin-top:40px;
    text-align: center;
    color:#2e2e2e;
    margin-bottom:40px;

}
img{
    width:300px;
    height:450px;
    border-radius: 10%;
}
.child{
    padding:20px;
}

contact.html
<html>
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>
    <div class="box">
        <h1>Contact us</h1><br><br>
        <p>We'd love to hear from you! Whether you have questions about our menu, want to make a reservation, or just want to share your dining experience, we're here to help.</p>
        <br><p>Phone: (123) 456-7890</p>
        <br><p>For inquiries, catering, or special events, reach out via email at cattlemansranch@contact.com . Follow us on social media for updates and specials. We cant wait to welcome you to our table!</p>
        <br><br><img src="https://lh3.googleusercontent.com/gps-cs-s/AG0ilSwGcwy2UeKYR8GGGafBa8cnwJ9-DfSSPQZYAaMj6TOLuIlqAKXud1EE0o1GVFO1SxNz5beSt3ueZD0JrHmskWYX0vZ-yvhiFfhXqjc6QvVAAVoE_bJiCf9R_2o4lVlzbCSIYnC42g=s1360-w1360-h1020-rw" alt="Restaurant Ambiance">
    </div>
  <footer>
    &copy;Designed and Developed by <span>DEVESH C(25011036)</span>
  </footer>
</body>
</html>

contact.css
*{
    padding:0%;
    margin:0%;

}
body{
    background-color:#00ffae;
    overflow-y: hidden;
}
.box{
    position:relative;
   
    top:60px;

    color:rgb(35, 12, 12);
    background-color:#1341d5;
    padding:10px;
    border-radius:5%;
    animation-name: anime;
    animation-duration:0.8s;
}
.box img{
    max-width:100%;
    max-height:300px;
    height:auto;
    border-radius: 2%;
    text-align: center;
    left:250px;
    position: relative;
    left:350px;
}
.box h1{
    text-align: center;
    color:#FDEBD0;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.4);
}
    footer {
      font-weight: bold;
      color: red;
      position: fixed;
      left: 0;
  bottom: 0;
  width: 100%;
    background-color: #f4f4f4;
    text-align: center;
     
    }

.box p{
    font-family: cursive;
}


```
## OUTPUT:
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (36).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
