# Ex.07 Restaurant Website
## Date:08.10.2025

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
        <title>Home</title>
        <link rel="stylesheet" href="home.css"> 
    </head>
    <body>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        </nav>
        <div class="name">
            <h1>APPANS RESTAURANT</h1>
            <b>"Delicious Food,made with Love"</b>
            
        </div>
        <div class="offer">
            <h2>Limited Time Offer</h2><br>
            <h3>Flat 50% OFF on Food Orders </h3><br>
            <h4>Order Now</h4>
        </div>
        <footer>
            <h6 class="bottom">V.Karthi-(25017522)</h6>

        </footer>
    </body>
</html>

home.css

*{
    margin: 0;
    border: 0;
}

body{
    background-image:url(restaurant.jpg);
    background-position: center;
    background-size:cover;
    width: 100%;
    background-color: rgb(252, 93, 24);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    color: rgb(15, 1, 1);
}

a{
    padding: 15px;
    color:rgb(232, 39, 5);
}
a:hover{
    background-color: rgb(125, 236, 15);
    color:rgb(237, 67, 15);
}
.name{
    text-align: center;
    position: relative;
    left: 290px;
    font-weight: bolder;
    font-family: 'Times New Roman', Times, serif;
    color: rgba(247, 9, 9, 0.855);
    font-size: 30px;
    width: 1000px;
    background-color: rgba(251, 246, 246, 0.94);
}
.offer{
    text-align: right;
    font-size: 40px;
    color: rgb(7, 247, 43);
    position: relative;
    right: 100px;
    top:200px;

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 462px;
    background-color: rgb(232, 248, 11);
}

menu.html

<html>
    <head>
        <title>Menu</title>
        <link rel="stylesheet" href="menu.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        </nav>
        <h1>Menu Lists</h1>
        <div class="main">
            
            <div class="food1">
                <img src="chicken biriyani.jpg"alt="pic">
                <b>CHICKEN BIRIYANI-$50</b>
            </div>
            <div class="food2">
                <img src="chicken noodles.jpg" alt="pic">
                <b>CHICKEN NOODLES-$45</b>
            </div>
            <div class="food3">
                <img src="grill chicken.jpg" alt="pic">
                <b>GRILL CHICKEN-$30</b>
            </div>
            <div class="food4">
                <img src="dosa.jpg" alt="pic">
                <b>DOSA-$20</b>
            </div>
            <div class="food5">
                <img src="idli.jpg" alt="pic">
                <b>IDLI-$10</b>
            </div>
            <div class="food6">
                <img src="poori.jpg" alt="pic">
                <b>POORI-$30</b>
            </div>
            <div class="food7">
                <img src="meals.jpg" alt="pic">
                <b>MEALS-$35</b>
            </div>
            <div class="food8">
                <img src="parotta.jpg" alt="pic">
                <b>PAROTTA-$25</b>
            </div>
            <div class="food9">
                <img src="pongal.jpg" alt="pic">
                <b>PONGAL-$40</b>
            </div>
            <div class="food10">
                <img src="shawarma.jpg" alt="pic">
                <b>SHAWARMA-$45</b>
            </div>
            
        </div>
        <footer>
            <h6 class="bottom">V.Karthi-(25017522)</h6>

        </footer>
    </body>
</html>

menu.css

body{
    
    background:url(restaurant2.jpg);
    background-repeat: no-repeat;
    background-position:center;
    background-size: cover;
    font-size: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    margin: auto;
}
.main{
    display: grid;
    grid-template-columns: repeat(5,1fr);
}
a{
    color:rgb(34, 221, 17);
    position: relative;
    left: 1200px;
}
.food1{
    padding: 10px;
    background-color: rgba(245, 45, 14, 0.993);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
}
.food2{
    padding: 10px;
    background-color: rgba(243, 9, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 30px;
    left: 80px;
    
}
.food3{
    padding: 10px;
    background-color: rgba(246, 28, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
}
.food4{
    padding: 10px;
    background-color: rgba(245, 16, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    bottom: 20px;
    left: 80px;
    
}
.food5{
    padding: 10px;
    background-color: rgba(255, 37, 8, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    bottom: 20px;
    
}
.food6{
    padding: 10px;
    background-color: rgba(244, 4, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food7{
    padding: 10px;
    background-color: rgba(247, 57, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food8{
    padding: 10px;
    background-color: rgba(239, 39, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food9{
    padding: 10px;
    background-color: rgba(250, 32, 4, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}
.food10{
    padding: 10px;
    background-color: rgba(252, 25, 9, 0.829);
    width: 180px;
    text-align: center;
    align-items: center;
    position: relative;
    left: 80px;
    
}


img{
    width: 150px;
    height: 100px;
    border: solid rgb(4, 4, 4) 6px;
}
h1{
    text-align: center;
    position: relative;
    bottom: 10px;
   
    color: rgb(10, 244, 170);

}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 50px;
    background-color: rgb(237, 212, 212);
}

admin.html

<html>
    <head>
        <title>Admin</title>
        <link rel="stylesheet" href="admin.css">
    </head>
    <body>
        <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        </nav>
        <h1>Administration</h1>
        <div class="admin">
            <div class="a1">
                <img src="vijay.jpg">
                <b>VIJAY</b><br>
                <b>CEO</b>
            </div>
            <div class="a2">
                <img src="rashmika.jpg">
                <b>RASHMIKA</b><br>
                <b>Manager</b>
            </div>
            <div class="a3">
                <img src="sachin.jpg">
                <b>SACHIN</b><br>
                <b>Service Manager</b>
            </div>
            <div class="a4">
                <img src="nayanthara.jpg">
                <b>NAYANTHARA</b><br>
                <b>Reception</b>
            </div>
            <div class="a5">
                <img src="ronaldo.jpg">
                <b>RONALDO</b><br>
                <b>Accounts Manager</b>
            </div>
            <div class="a6">
                <img src="ambani.jpg">
                <b>AMBANI</b><br>
                <b>Maintenance Manager</b>
            </div>
        </div>
        <footer>
            <h6 class="bottom">V.Karthi-(25017522)</h6>

        </footer>
    </body>
</html>

admin.css

body{
    background-image:url(restaurant4.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
a{
    padding: 15px;
    color:rgb(88, 245, 3);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
    font-size: x-large;
}
.admin{
    display: grid;
    grid-template-columns: repeat(6,1fr);
    font-size: 20px;
    gap:10px;
}
img{
    width: 210px;
    height: 300px;
    border:solid 5px rgb(195, 68, 68);
}
.a1,.a2,.a3,.a4,.a5,.a6{
    padding: 5px;
    background-color: rgb(246, 237, 237);
    text-align: center;
    font-size: 24px;
    
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color:white;
    position: relative;
    top: 60px;
    color:white;
}
h1{
    text-align: center;
    color:rgb(243, 245, 235);
    font-size: 40px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 125px;
    background-color: brown;
    width: 1550px;
}


contact.html

<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="contact.css">
    </head>
    <body>
         <nav>
            <a  href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact</a>
        </nav>
        <div class="contact-container">
            <h1>Contact Us:</h1>
            <h4>Address: No:69,West Tambaram,Chennai,Tamilnadu</h4>
            <h2>Phone no: +91 1234567890</h2>
            <h3>Email:AppansRest@gmail.com</h3>
        </div>
        <footer>
            <h6 class="bottom">V.Karthi-(25017522)</h6>

        </footer>
    </body>
</html>


contact.css

body{
    background-image:url(restaurant3.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    font-size: 20px;
}

a{
    padding: 15px;
    color:rgb(85, 246, 11);
    position: relative;
    left: 1100px;
    top: 20px;
    font-size: 20px;
}
.bottom{
    font-size: 30px;
    text-align: center;
    background-color: rgba(9, 8, 8, 0.768);
    position: relative;
    top: 150px;
    color: white;
}
.contact-container{
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
    padding: 30px;
    background-color: rgb(251, 246, 246);
    height:400px;
    width:410px;
    display: block;
    gap: 20px;
    font-size: 20px;
    position: relative;
    left: 600px;
    top:20px;
    border-radius: 10%;
}
h2,h3,h4{
    font-size: 27px;
}
```

## OUTPUT:
![alt text](<Screenshot (123).png>)
![alt text](<Screenshot (124).png>)
![alt text](<Screenshot (125).png>)
![alt text](<Screenshot (126).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
