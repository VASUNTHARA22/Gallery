# Ex.08 Design of Interactive Image Gallery
# Date:16.11.2024
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Image Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1> TOURIST PLACE </h1>
    </header>
    <div class="gallery">
        <div class="gallery-item" onclick="openModal(this)">
            <img src="gal 1.jpeg" >
        </div>
        <div class="gallery-item" onclick="openModal(this)">
            <img src="gal 2.jpeg"  >
        </div>
        <div class="gallery-item" onclick="openModal(this)">
            <img src="gal 3.jpeg" >
        </div>
        <div class="gallery-item" onclick="openModal(this)">
            <img src="gal 4.jpeg" >
        </div>
    </div>

    <div id="modal" class="modal">
        <span class="close" onclick="closeModal()">&times;</span>
        <img class="modal-content" id="modalImage">
        <div id="caption"></div>
    </div>

    <script src="style.js"></script>
</body>
</html>
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/a7b04fa8-5073-4699-93d6-221a54af91d8)

![image](https://github.com/user-attachments/assets/0f1a3002-6833-4d72-a1d1-3270806f2698)

![image](https://github.com/user-attachments/assets/7f8c6262-3aac-4fe8-acdd-469bd365c03e)

![image](https://github.com/user-attachments/assets/94e1112c-3b2d-4036-950d-1ec667db197c)

![image](https://github.com/user-attachments/assets/4c115c1a-4a4d-426b-9a68-46aa82967289)


# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
