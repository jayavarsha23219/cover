# Ex.06 Book Front Cover Page Design
## Date:15.04.2024

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
    <title>CSE</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(img2.jpeg);
            background-size: cover;
        }
            
        
        .insight{
            color:wheat;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 255, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:purple;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 20px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        
        .ed{
            color:purple;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:purple;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:250px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 50px;
            background-size:contain;
        }

        .p {
        font-size: medium;
        font-family: Arial, Helvetica, sans-serif;
        position: relative;
        top: 40px;
        }

        .publisher {
        font-size: large;
        position: relative;
        top: 135px;
        left: 330px;
       }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">SEC INSIGHT</div>

            <div class="hrstyle">
                <hr style="color:mediumaquamarine">
            </div>
            <div class="booktitle">
                <h1>Developing Web Application Using MVC </h1>
            </div>
            <div class="p">
                <p>
                    The MVC pattern for a specific aspect of the application's functionality.
                </p>
            </div>
            <div class="mypic">
                <img src="img.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:mediumaquamarine">
            </div>
            <div class="author">
               <p><b>JAYAVARSHA T </b></p>
            </div>
            <div class="publisher">
                <b> SEC </b>
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
</html>
```

## OUTPUT:
![alt text](<cover page output.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
