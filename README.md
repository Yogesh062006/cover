# Ex.06 Book Front Cover Page Design
## Date:29/04/2025

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
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Front Page</title>
    <style>
        /* Basic styles */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: blue;
        }

        .book-cover {
            position: relative;
            width: 100%;
            height: 100vh;
            background-image: url('your-image.jpg'); /* Replace with your book cover image */
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding-top: 150px;
        }

        .book-title {
            font-size: 3em;
            font-weight: bold;
            margin-bottom: 20px;
        }

        .author {
            font-size: 1.5em;
            font-style: italic;
        }

        .description {
            font-size: 1.2em;
            margin-top: 30px;
            max-width: 80%;
            margin-left: auto;
            margin-right: auto;
        }
    </style>
</head>
<body>

    <div class="book-cover">
        <div class="book-title">The Great Adventure</div>
        <div class="author">By Yogesh</div>
        <div class="description">
            An epic tale of exploration, bravery, and the journey of self-discovery. Join our protagonist as they traverse unknown lands and face unimaginable challenges.
        </div>
    </div>

</body>
</html>



## OUTPUT:
![Screenshot 2025-04-29 150112](https://github.com/user-attachments/assets/699d66f2-803c-4c61-a043-54d0ab68db9e)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
