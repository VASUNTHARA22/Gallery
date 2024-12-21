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
![image](https://github.com/user-attachments/assets/2dff810b-eaef-456f-b19c-c8aa2ed7c404)

![image](https://github.com/user-attachments/assets/6b86ff10-2f26-4b29-9363-8a080fc24e44)

![image](https://github.com/user-attachments/assets/f7c6f1e3-90e4-4b22-aa84-9d4f1ebf5a77)

![image](https://github.com/user-attachments/assets/3057897a-9ec6-4562-a099-cb32cf0c32ce)

![image](https://github.com/user-attachments/assets/380f1eef-b251-4ff3-8731-5111362a9c87)

# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
