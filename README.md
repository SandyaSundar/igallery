# Ex.08 Design of Interactive Image Gallery
## Date: 18/10/2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
gallery.html
<html>
    <head>
        <title>Interactive Image Gallery</title>
        <link rel="stylesheet" href="style.css">
        <script src="script.js"></script>
    </head>
    <body>
        <br>
        <h1>MY IMAGE GALLERY</h1><hr><br>
        <h3>Sandya S - 25017264</h3><br><br><br><br>
        <div class="gallery">
            <img id="photo1" src="IMG-20220507-WA0019.jpg" onmouseover="mouseIn(this)" onmouseout="mouseOut(this)">
             <img id="photo1" src="WhatsApp Image 2025-10-18 at 23.49.23_46cc2a7a.jpg" onmouseover="mouseIn(this)" onmouseout="mouseOut(this)">
              <img id="photo1" src="IMG_20230519_143042.jpg" onmouseover="mouseIn(this)" onmouseout="mouseOut(this)">
              <img id="photo1" src="IMG_20230516_173153.jpg" onmouseover="mouseIn(this)" onmouseout="mouseOut(this)">
                <img id="photo1" src="IMG-20210405-WA0042.jpg" onmouseover="mouseIn(this)" onmouseout="mouseOut(this)">
        </div>
    </body>
</html>

style.css
body {
  text-align: center;
  background-color: brown;
  font: Arial;
}

h2 {
  color: black;
}

.gallery {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}

.gallery img {
  width: 230px;
  height: 300px;
  border-radius: 8px;
  transition: all 0.3s ease;
  box-shadow: 0 2px 8px black;
  cursor: pointer;
}

script.js
function mouseIn(img) {
    img.style.width = "300px";
    img.style.height = "370px";
    img.style.boxShadow = "0 8px 20px black";
    img.style.border = "3px solid grey";
}

function mouseOut(img) {
    img.style.width = "230px";
    img.style.height = "300px";
    img.style.boxShadow = "0 2px 8px black";
}

```

## OUTPUT:
![alt text](<Screenshot (49).png>)
![alt text](<Screenshot (51).png>)





## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
