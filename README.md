# Ex.06 Book Front Cover Page Design
## Date:05/04/2024

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
<!DOCTYPE html>
<html>/

<head>
    <title>CYBER SECURITY</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(back.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(214, 230, 230);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(162, 29, 135);
            top:270px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(243, 234, 236);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:rgb(214, 219, 219);
            font-size: medium;
            position: relative;
            top:235px;
            left:330px;
        }
        .ed{
            color:rgb(226, 234, 234);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:190px;
        
        }
        .subtitle{
            color:rgb(225, 231, 231);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(230, 238, 228)">
            </div>
            <div class="booktitle">
                <h1>CYBER SECURITY IN INDIA</h1></div>
            <div class="subtitle">
                 USING AI IN 
                 
            </div>
            <div class="subtitle">
                 CYBER SECURITY
            </div>

            <div class="mypic">
                <img src="photo.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(224, 229, 224)">
            </div>
            <div class="author">
               <p><b>KEERTHANASIVAKUMAR</b></p>
            </div>
            <div class="pub">
                   SEC
            </div>
            <div class="ed">
                <b> EXTENDED EDITION</b>
            </div>
        </div>
        </body>
        

</html>



```

## OUTPUT:

![bookcover2](https://github.com/keerthanasivakumar02/cover/assets/150827397/7878b39e-f1ad-4810-9ef1-2f15c30031e1)




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
