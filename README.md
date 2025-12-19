# Ex.07 Restaurant Website
# Date:
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
food.html
```
<html>
    <head>
        <title> web page</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div id="topbar"></div>
        <div id="placement">
            <div id="header">
                <img src="logo.jpg" />
                <ul>
                    <li><a href="home.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="contactus.html">Contact Us</a></li>
                    <li><a href="aboutus.html">About us</a></li>
                    <li><a href="chef.html">Administration</a></li>
                </ul>
            </div>
            <div id="banner">
                <img src="feast.webp"/>
            </div>
            <div id="content1">
                <h4 class="heading">WELCOME</h4>
                <p class="para">
                    Hey there!

                Thanks for joining/ordering. We’re thrilled to have you.

                    Welcome to Home Foods! Get ready for some amazing deals and updates right here. 
                </p>
            </div>
            <div id="content2">
                <h4 class="heading2">About Us</h4>
                <ul class="list">
                <li>Passion for Freshness.</li>
                <li>Crafted by Experts.</li>
                <li>Healthy & Wholesome.</li>
                <li>Fast & Reliable Delivery.</li>
            </ul>
            </div>
            <div id="content3">
                <h4 class="heading3">SERVICE</h4>
                <p class="para1">We offer delicious dine-in, takeaway, and online delivery services. Our expert chefs craft fresh, healthy meals daily, ensuring great taste, fast service.</p>
            </div>
            <div id="bottom">
                <h2 class="address">Address:</h2>
                <p class="para2">3, Coral Garden Road, Adyar, Chennai - 600020</p>
                </div>
                <div id="bottom2">
                <h2>Ambiance</h2>
                <img src="res.jpg" class="image" width="450px" height="250px"/>
            </div>
        </div>
        <div id="footer">
            <ul>
                <h4 align="center">designed by monsh.s </h4>
            </ul>
        </div>
    </body>
</html>

home.html

<html>
    <head>
        <title>
            home page
        </title>
    </head>
    <body bgcolor="beige">
        <h2>HOME</h2>
        <p>Discover the true taste of freshness and flavor at Spice Haven, where every meal is made with love and passion. From traditional Indian curries to modern fusion dishes, our chefs craft every plate using the finest ingredients. Dine with us for a cozy experience, or order online for fast delivery straight to your door. Enjoy delicious food, warm hospitality, and unforgettable taste — all in one place.</p>
    </body>
</html>

menu.html

<html>
    <head>
        <title>Menu</title>
    </head>
    <body bgcolor="wheat">
        <h2>MENU</h2>
        <h4>Crispy Veg Spring Rolls</h4>
        <h4>Paneer Tikka</h4>
        <h4>Chicken 65</h4>
        <h4>Pepper Prawns</h4>
        <h4>Butter Chicken with Naan </h4>
        <h4>Paneer Butter Masala</h4>
        <h4>Veg Biryani</h4>
        <h4>Chicken Dum Biryani </h4>
    </body>
</html>

aboutus.html

<html>
    <head>
        <title>
            About Us
        </title>
    </head>
    <body bgcolor="sky blue">
        <h3>ABOUT US</h3>
        <h4>At home food, we believe great food brings people together. Our chefs create flavorful dishes using fresh, local ingredients, blending tradition with innovation to deliver an unforgettable dining experience every time.</h4>
    </body>
</html>

contactus.html

<html>
    <head>
        <title>
            Contact Us
        </title>
    </head>
    <body bgcolor="yellow">
        <h2>CONTACT US THROUGH</h2>
        <h3>Email:homefood@gmail.com</h3>
        <h3>Phone: 9898232312</h3>
    </body>
</html>

chef.html

<html>
    <head>
        <title>administration</title>
    </head>
    <body align="center">
        <h1>Administrative People</h1>
    <div class="card1"><img src="chef2.webp">
        <h3>Mr.Damodaran</h3>
        <p>Head Chef</p>
        <hr>
    </div>
    <div class="card2"><img src="chef 1.jpg">
        <h3>Mr. Venkatesh Bhat</h3>
        <p>Pastry Chef</p>
        <hr>
    </div>
    
    <div class="card3"><img src="chef5.webp" >
        <h3>Mr. Madhampatty Rangaraj</h3>
        <p>Assistant Chef</p>
        <hr>
    </div>
    <div class="card4"><img src="chef3.webp">
        <h3>Mr. Deena</h3>
        <p>Public Relations</p>
        <hr>
    </div>
    </body>

<h4>HOME FOOD</h4>
<h4>Designed by NITHISH R</h4>

</html>

style.css

#topbar
{
    background-color: black;
    height:10px;
    width:100%;
}
body{
    background-color: white;
}

#placement
{
    background-color:beige;
    width: 75%;
    margin: 0px auto;   
}
#header
{
    height: 80px;
    width: 100%;
    background-color: white;
}
#header img
{
    height: 80px;
    width: 10%;
}
#header ul
{
    float: right;
    margin-top: 25px;
}
#header ul li
{
    display:inline;
    margin-right:50px;
    font-size: 20px;  
}
#header ul li a
{
    color: black;
    text-decoration: none;
}
#banner img
{
    width:100%;
    height: 60%;
    padding-bottom: 20px;
}
#content1
{
    width:30%;
    height: 200 px;
    background-color: darkorange;
    float: left;
    margin-right:3%;
}
#content2
{
    width:30%;
    height: 200 px;
    background-color: rgb(163, 163, 87);
    float: left;
    margin-right: 3%;
}
#content3
{
    width:30%;
    height: 200 px;
    background-color: yellowgreen;
    float:right;
    margin-right: 3%;
}
.heading
{
    color:white;
    margin-left: 10px;
}
.para
{
    color: white;
    margin-left: 10px;
}
.heading2
{
    color: white;
    margin-left: 10px;
}
.list
{
    color: white;
    margin-left: 10px;
}
.heading3
{
    color: white;
    margin-left: 10px;
}
.para1
{
    color: white;
    margin-left: 10px;
}
#bottom
{
   width: 60%;
   float: left; 
   padding-top: 10px;
}
.address
{
    color:black;
    
}
.para2
{
    color: black;
}
#bottom2
{
    width: 40%;
    padding-top: 10px;
    float: right;
}
#bottom2 h4
{
    color: black;
}
.image
{
    float: right;
    padding-top: 10px;
}
#footer
{
    width: 100%;
    height:30px;
    background-color: black;
    clear: both;
}
#footer ul h4
{
    padding-top: 10px;
    color: white;
}
```
# OUTPUT:
<img width="1920" height="1080" alt="front1" src="https://github.com/user-attachments/assets/d6ebf97d-d09d-46a6-924b-d889a9bb3366" />
<img width="1920" height="1025" alt="front2" src="https://github.com/user-attachments/assets/29ecd0ef-cc20-4563-8793-7e54830fd040" />
<img width="1920" height="1080" alt="home" src="https://github.com/user-attachments/assets/55c668ae-81b9-4cd2-bec3-7ccf6eef1d48" />
<img width="1920" height="1080" alt="menu" src="https://github.com/user-attachments/assets/ed4d0de7-c98e-401a-b5eb-537bc12fa19c" />
<img width="1920" height="1080" alt="about" src="https://github.com/user-attachments/assets/ecc0a5f0-9b3d-45ca-87ff-211d43dfd215" />
<img width="1920" height="1080" alt="t4" src="https://github.com/user-attachments/assets/28618e13-7623-417e-b613-bfe0d36188c2" />
<img width="1920" height="1080" alt="t5" src="https://github.com/user-attachments/assets/debe269f-dba0-41a7-a0b4-b42294c85131" />

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
