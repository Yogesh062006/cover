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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Front Page</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f5f0e1; /* Page background */
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .book-cover {
            width: 400px;
            height: 600px;
            background-color: #1e3a5f; /* Book cover color - dark blue */
            color: white;
            box-shadow: 0 0 30px rgba(0, 0, 0, 0.6);
            border: 2px solid #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
        }

        .book-title {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }

        .author {
            font-size: 1.2em;
            font-style: italic;
            margin-bottom: 20px;
        }

        .description {
            font-size: 1em;
            background-color: rgba(0, 0, 0, 0.3);
            padding: 10px;
            border-radius: 8px;
            line-height: 1.4em;
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
```





## OUTPUT:
![Screenshot 2025-04-29 182955](https://github.com/user-attachments/assets/bb5cf775-0188-4ef7-8c9d-01982b523ecf)




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
