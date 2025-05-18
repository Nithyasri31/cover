# Ex.06 Book Front Cover Page Design
## Date:18/05/2025

## AIM:
To design a book front cover page using HTML and CSS.

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
<html>
    <head>
        <style>
            body 
            {
                margin: 0;
                padding: 0;
                background-color: rgb(255, 255, 255);
                
            }
            .container 
            {
                position: relative; 
                width: 400px; 
                height: 600px; 
                margin: 5px auto; 
                background-image: url(webimg.jpeg);
                background-size: contain; 
               
            }
            .heading
             {
                position: absolute;
                top: 130px;
                left: 5px;
                text-align: center;
                letter-spacing: 3;
                font-family:Impact,'Haettenschweiler','Arial Narrow Bold', sans-serif;
                font-weight: 225;
                margin: 1;
                border-top: 6px black;
                border-bottom: 6px solid black;
                box-shadow: 0 4px 6px black;
                padding-bottom: 5px;
            }
            .sideheading
            {
                position: absolute;
                top: 50px;
                right: 30px;
                text-align: right;
                letter-spacing: 3;
                font-size: 8;
                margin: 0;

            }
            .authorimage
             {
                position: absolute; 
                bottom: 130px; 
                right: 40px; 
                width: 80px; 
            }
            .authorname
             {
                position: absolute;
                bottom: 100px;
                right: 25px; 
                font-size: 15px;
                font-family:'Gill Sans', 'Gill Sans MT','Calibri','Trebuchet MS','sans-serif';
                color: rgb(174, 72, 202);
                margin: 0;
            }
            .edition
            {
              position: absolute;
                bottom: 50px;
                left:20px;
                text-align: left;
                letter-spacing: 3;
                font-size:15;
                margin: 0;
            }
            .regno
            {
              position:absolute;
              bottom:5px;
              right: 50px;
              font-size: small;
              font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode','Geneva','Verdana','sans-serif';
              font-style: normal;
              color: rgb(6, 6, 6);
              margin: auto;
            }
        </style>
        <title>BOOK COVER</title>
    </head>
    <body>
        <div class="container">
            <h1 class="heading">Tales Under The Purple Sky</h1>
            <h2 class="authorname">NITHYASRI M</h2>
            <h3 class="sideheading">EXPERT SIGHT</h3>
            <img src="img.jpg" class="authorimage">
            <h5 class="edition">2028 EDITION</h5>
        </div>
    </body>
</html>


```
## OUTPUT:

![alt text](<Screenshot 2025-05-18 160310.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
