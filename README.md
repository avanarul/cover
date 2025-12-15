# Ex.05 Book Cover Page Design
## Date:15.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html


<html>
    <head>
        <title>Book Cover</title>
        <link href='style.css' rel="stylesheet">
    </head>
    <body>
        <div class="top">
        <h1>About the Book</h1>
        <hr>
        <p>About <p2>the book cryptocurrency"</p2> is a general request that does not refer to a specific title, as there are many books on the subject. These books cover a wide range of topics, from basic introductions for beginners to in-depth guides for investors, developers, and legal professionals. </p>
                   
        <div class="no1">
            <p1>&quot;Data science is the art of turning raw data into knowledge that drives better decisions.&quot;</p1>
            </div>
            <div class="no2">
            <p1>S Avan Arul</p1>
            <p3>Avan Arul is a technology writer, blockchain enthusiast, and financial educator dedicated to making the world of digital assets accessible to all. With a background in computer science and finance, Avan has spent years exploring the evolution of decentralized systems, smart contracts, and the economic forces shaping the future of money.</p3>
            </div>
            <div class="no3">
            <p4>SEC Publishers</p4>
            <p5 class="lastbox">Printed in India</p5>
            <p6 class="rate">Price: rs:999</p6>
        </div>
    </body>
</html>

style.css

body{
    background-image: url("2YApK1y9zA9YquHMxj8yfvFH7ul-mobile.jpg");
    background-size: contain;
    margin-left: 515px;
    margin-right: 515px;
    background-repeat: no-repeat;
    background-position: center;
}
.top{
    color: white;
}

p{
    margin-left: 10px;
    margin-right: 10px;
}

.no1{
    padding:12px;
    height: 60px;
    font-size: 22px;
    border-left:white 4px solid;
    background-color:pink;
    font-style:italic;
    border-radius: 15px;
}

p>p2{
    background-color:red;
}

.no2 {
    margin-top:38px;
    background-image: url("WhatsApp Image 2025-12-15 at 22.55.42_4c40cb2c.jpg");
    background-repeat:no-repeat;
    background-size: contain;
    background-position: 10px 18px;
    background-size: 85px 85px;
    padding:10px;
    height: 100px;
    font-size: 15px;
    background-color:yellowgreen;
    font-style:italic;
    padding-left: 100px;
    border-radius: 15px;
    font-size:small;
}

.no3 {
    margin-top:200px;
    padding:10px;
    height: 60px;
    color:white;
    font-size: 18px;
    background-color: blue;
}

.lastbox{
    color:white;
}

.rate{
margin-left:140px;
}

```

## OUTPUT:
![alt text](<cover/johnapp/static/Screenshot 2025-12-15 230615.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
