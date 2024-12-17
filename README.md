# Ex.06 Book Front Cover Page Design
## Date:02.11.2024

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Book Cover </title>
    <style>

        .container {
            width: 100px; 
            height: 600px; 
            background-image: url(img2.jpg);
            background-position: center;
            text-align: center;
        }
        .background {
            width: 700%;
            height: 150%;
        }
        .overlay {
            position: absolute;
            top: 30px; 
            right: 900px; 
            width: 500px; 
            height: auto; 
            bottom: 70px; 
            
        }

    </style>
</head>
<body>

<div class="container">
    <img src="img2.jpg" alt="background" class="background">
    
        <img src="img1.jpg" alt="overlay" class="overlay">

        <img src="l2.png" alt="overlay" class="overlay-container">
    </div>
</body>
</html>

<head>
    <style>
        .overlay-container {
            position: relative;
            width: 500px; 
            height: 300px; 
            background-image: url('background.jpg');
            background-size: cover;
        }
        .overlay {
            background-image: url('overlay.png');
            background-size: contain;
            position: center;
            bottom: 30px;
            right: width 900px;
            width: 550px;
            height: 850px;
         }
         .overlay-container {
            background-image: url('overlay.png');
            background-size: contain;
            position: center;
            bottom: 250px;
            right: width 600px;
            width: 200px;
            height: 130px;
            left: 240px;

         }   
        
        .text {
            position: absolute;
            top: -120%; 
            left: 50%; 
            transform: translate(-50%, -50%); 
            text-align: center; 
            font-size:xx-large;
            color: brown;
            font-family:initial;
        }
    </style>
    
</head>
<body>
    <div class="overlay-container">
    <div class="overlay"></div>
    <div class="text"><h2>~THE~ ART  OF  ~NATURE~</h2></div>
    <div class="text"><h4><br><br><br><br><br><br><br><br><br><br><br><br><br><hr color="black">"Nature brush never rests,creating wonders that remind us of the beauty in simplicity"<br></h4></div>
    <div class="text"><h6><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
        <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>A Novel By<br>SAM</h6></div>
        
</div>
</body>
</html>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-17 150533.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
