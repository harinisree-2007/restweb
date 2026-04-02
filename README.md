# Ex.06 Complex Problem: Restaurant Website
## Date:02.04.2026

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
Publish the website in Localhost.


## PROGRAM:
home.html
```
<html>
    <head>
        <title>Home</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">Flavours of Chettinadu</h1>
        <h2 class="subtitle">The flavours of chettinadu and south indian food</h2>
        <p style="margin-left:80px;">
            Tamil Nadu's Chettinad region, is famous for its bold spices, rich flavors, and aromatic dishes
        </p>
        <div class="image-container">
            <img src="img.1.jpg">
            <img src="img.2.jpg">
            <img src="img.3.webp">
        </div>
        <footer>NAME-HARINI SREE N, REF NO:25015936</footer>
    </body>
</html>


menu.html
<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">MENU</h1>
        <div class="menu-container">
            

            <div class="card">
                <img src="thokku briyani.avif">
                <h3>Thokku Briyani</h3>
                <p>Rs.550</p>
            </div>
            <div class="card">
                <img src="mutton chukka.jpg">
                <h3>mutton chukka</h3>
                <p>Rs.450</p>
            </div>
            
            <div class="card">
                <img src="idiyappam.jpg">
                <h3>idiyappam chicken</h3>
                <p>Rs.340</p>
            </div>

            <div class="card">
                <img src="Pallipalayam-chicken.jpg">
                <h3>chicken pallipalayam</h3>
                <p>Rs.160</p>
            </div>

            <div class="card">
                <img src="kulambu.webp">
                <h3>Chicken kulambu</h3>
                <p>Rs.300</p>
            </div>

            <div class="card">
                <img src="naatu kozhi.jpg">
                <h3>Naattu kozhi varuval</h3>
                <p>Rs.530</p>
            </div>

        </div>

        <footer>NAME-HARINI SREE N, REF NO:25015936</footer>
    
    </body>
</html>

admin.html
<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">ADMINISTRATION TEAM</h1>
        <div class="team-container">
            <div class="team-card">
                <img src="harini sree.jpeg">
                <h3>Harini Sree N</h3>
                <p>owner</p>
            </div>
            <div class="team-card">
                <img src="sk...jpg">
                <h3>SK</h3>
                <p>chef</p>

            </div>

            <div class="team-card">
                <img src="suriya.jpg">
                <h3>Suriya</h3>
                <p>assistant chef</p>
            </div>

            <div class="team-card">
                <img src="karthi.jpg">
                <h3>Karthi</h3>
                <p>customer service manager</p>
            </div>
            <div class="team-card">
                <img src="danish.jpg">
                <h3>Danish</h3>
                <p>food manager </p>
            </div>
        </div>
        <footer>NAME-HARINI SREE N , REF NO:25015936</footer>
    </body>
</html>

contact.html
<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <nav>
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </nav>
        <h1 class="main-title">CONTACT</h1>
        <div class="contact-box">
            <h2>Visit us At:</h2>
            <p>
                flavours of chettinadu
                <br>
                6th cross street,city corner
                <br>
                chettinadu
                <br>
                Tamil Nadu
            </p>
            <br>
            <h2>Phone:</h2>
            <p>+91 9621131946</p>
            <br>
            <h2>Email ID:</h2>
            <p>flavoursofchettinadu@gmail.com</p>
        </div>
        <footer>NAME-HARINI SREE N , REF NO:25015936</footer>
    </body>
</html>
```
style.css
```
body{
    background-image:url(download.avif);
    background-size:cover;
    background-position:center;
    color:white;
    padding:fixed;
    margin:0;
    bottom:0;
    box-sizing:border-box;
    font-family:Arial;
}

nav{
    position:absolute;
    top:20px;
    right:80px;
    background:linear-gradient(45deg,rgb(239, 141, 88),rgb(247, 148, 10));
    padding:12px 40px;
}

nav a{
    margin:0 20px;
    text-decoration:none;
    color:rgba(103, 34, 9, 0.797);
    font-weight:bold;
}

.main-title{
    font-size:90px;
    color:rgba(216, 112, 20, 0.829);
    margin-left:80px;
    margin-top:120px;
}

.subtitle{
    font-size:30px;
    margin-left:80px;
}

.image-container{
    display:flex;
    justify-content:center;
    gap:80px;
    margin-top:40px;
}

.image-container img{
    width:450px;
    border-radius:10px;
}

.menu-container{
    display:flex;
    justify-content:center;
    gap:25px;
    margin-top:400px;
}

.card{
    background:linear-gradient(45deg,rgba(220, 45, 6, 0.715),rgba(206, 92, 31, 0.852));;
    padding:15px;
    border-radius:12px;
    text-align:center;
    width:150px;
    color:black;
}

.card img{
    width:100%;
    border-radius:10px;
}

.card h3{
    margin-top:10px;
}

.card p{
    margin-top:5px;
}

.team-container{
    display:flex;
    justify-content:center;
    gap:30px;
    margin-top:350px;
}

.team-card{
    background:linear-gradient(45deg,rgb(61, 48, 244),rgb(158, 116, 36));
    width:180px;
    padding:20px;
    border-radius:15px;
    text-align:center;
    color:black;
}

.team-card img{
    width:120px;
    height:120px;
    border-radius:40%;
}

.team-card h3{
    margin-top:10px;
}

.contact-box{
    margin-left:90px;
    margin-top:40px;
    line-height:35px;
}

footer{
    text-align:center;
    padding:10px;
    background:linear-gradient(45deg,rgb(32, 203, 237),black,rgba(233, 201, 140, 0.868));
    color:whitesmoke;
    position:fixed;
    bottom:0;
    width:100%;
}


```
## OUTPUT:
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-8.png)
![alt text](image-9.png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
