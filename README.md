# Ex.06 Book Front Cover Page Design
## Date:4.12.2024

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
            body {
                margin: 10;
                padding: 0;
                background-color: #b6b6b6; 
            }
            .container {
                position: relative; 
                width: 360px; 
                height: 500px; 
                margin: 5px auto; 
                background-image: url(wp2987144.jpg);
                background-size: contain; 
                border: 2px solid rgb(255, 255, 255);
            }
            .title {
                position: absolute;
                letter-spacing: 5;
                top: 50px;
                left: 45px;
                color: antiquewhite;
                text-align: left;
                font-family:sans-serif;
                font-size: 15px;
                font-weight: 50;
                margin: 0;
            }
            .sub{
                position: absolute;
                letter-spacing: 5;
                top: 54px;
                left: 45px;
                color:white;
                text-align: left;
                font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
                font-weight: 150;
                margin: 0;
            }
            .edition{
                position: absolute;
                letter-spacing: 3;
                top: 450px;
                left: 25px;
                color:aliceblue;
                text-align: right;
                font-size: 8;
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                font-weight: 15;
                margin: 0;

            }
            .imag {
                position: absolute; 
                bottom: 20px; 
                right: 15px; 
                width: 80px; 
                border-radius: 5%;
                border: 2px solid rgb(223, 229, 230); 
            }
            .imag1 {
                position: absolute; 
                top: 180px; 
                right: 110px; 
                height: 150px;
                width: 150px; 
                border-radius: 5%;
                color:aliceblue;
                border: 2px solid rgb(255, 255, 255);
                
            }
            .author {
                position: absolute;
                bottom: 8px;
                left: 22px; 
                font-size: 15px;
                font-family: Arial, Helvetica, sans-serif;
                color: rgb(228, 241, 241);
                letter-spacing: 3;
                margin: 0;
            }
        </style>
        <title>My Book</title>
    </head>
    <body>
        <div class="container">
            <h1 class="title">Introduction to</h1>
            <h2 class="sub"><b><br>APPLICATION OF WEB AND CSS</br></b></h2>
            <img src="kkk1.jpeg" class="imag">
            <img src="pngegg.png" class="imag1">
            <h4 class="author">SYED KASHIF S</h4>
            <h6 class="edition">48th EDITION</h6>
        </div>
        
    </body>
</html>
```
## OUTPUT:
![alt text](<Screenshot (12).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
