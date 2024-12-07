# Ex.06 Book Front Cover Page Design
# Date:22/10/2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            background-color: #fcfafa; /* Light background for preview */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Times New Roman', Times, serif;
        }      

        .book-cover {
            width: 400px;
            height: 600px;
            background-color: #2c3e50; /* Dark blue background for the cover */
            border: 5px solid #1a252f; /* Outer border */
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.5); /* Shadow for a 3D effect */
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            align-items: center;
            padding: 30px;
            color: white; /* Text color for contrast */
            text-align: center;
        }

        .book-title {
            font-size: 32px;
            font-weight: bold;
            margin: 0;
            line-height: 1.2;
        }

        .book-subtitle {
            font-size: 20px;
            font-style: italic;
            margin: 10px 0;
        }

        .author {
            font-size: 18px;
            font-style: italic;
            margin-top: 20px;
        }

        .description {
            font-size: 14px;
            margin-top: auto;
            line-height: 1.5;
        }

        .decorative-line {
            height: 4px;
            width: 60%;
            background-color: #e74c3c; /* Red decorative line */
            margin: 10px auto;
        }

        .center-image {
            width: 150px; /* Set the size of the image */
            height: auto;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div>
            <h1 class="book-title">Between</h1>
            <h2 class="book-title">Two Worlds</h2>
            <div class="decorative-line"></div>
        </div>
        <img src="imagemap image.jpg" alt="Decorative Image" class="center-image"> <!-- Small image in the center -->
        <div class="author">- Leon</div>
        <div class="description">
            A heartwarming romance that defies the odds, proving that love knows no boundaries.
        </div>
    </div>
</body>
</html>


```
# OUTPUT:

![Screenshot 2024-12-07 214916](https://github.com/user-attachments/assets/945b2614-e34f-466d-8727-900795dea3c3)


![Screenshot 2024-12-07 215000](https://github.com/user-attachments/assets/0c0459e6-6b7c-4f38-895b-a458a96606ee)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
