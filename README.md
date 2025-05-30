# Ex.06 Book Front Cover Page Design
# Date: 24/04/2025
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
book.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Book Cover</title>
</head>
<body>
    <div class="book-cover">
        <div class="header">SEC INSIGHT</div>
        <div class="title-container">
            <div class="title">Web Development:</div>
            <div class="subtitle">The Complete Reference</div>
        </div>
        <div class="insights">with Django and Bootstrap Insights</div>
        <img src="author.jpg" alt="Author" class="author-picture">
        <div class="bottom-section">
            <div class="extended">Extended Edition</div>
            <div class="author-sec">
                <div class="author">Dr. R. Selvakumar</div>
                <div class="sec-logo">SEC</div>
            </div>
        </div>
    </div>
</body>
</html>

styles.css

body {
    margin: 0;
    padding: 0;
    height: 100vh;
    background-color: white; 
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: monospace, 'Courier New', Courier;
}

.book-cover {
    width: 400px;
    height: 600px;
    background: url('background.jpg') center/cover no-repeat; 
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    text-align: center;
    position: relative;
    padding: 20px;
    box-sizing: border-box;
}

.header {
    font-size: 18px;
    font-weight: bold;
    color: white;
    text-transform: uppercase;
    align-self: flex-start;
    margin-bottom: 40px;
    padding-bottom: 5px;
    border-bottom: 2px solid white;
    width: 100%;
}

.title-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 40px;
    margin-bottom: 20px;
}

.title {
    font-size: 36px;
    color: white;
    font-weight: bold;
    margin-bottom: 10px;
}

.subtitle {
    font-size: 36px;
    color: white;
    font-weight: bold;
}

.insights {
    font-size: 20px;
    color: white;
    margin-top: 40px;
}

.author-picture {
    width: 100px;
    height: 120px;
    border: 2px solid white;
    position: absolute;
    bottom: 80px;
    right: 20px;
}

.bottom-section {
    position: absolute;
    bottom: 20px;
    width: calc(100% - 40px);
}

.extended {
    font-size: 18px;
    font-weight: bold;
    color: white;
    text-transform: uppercase;
    margin-bottom: 10px;
    padding-bottom: 5px;
    border-bottom: 2px solid white;
    text-align: left;
}

.author-sec {
    display: flex;
    justify-content: space-between;
    width: 100%;
}

.author {
    font-size: 18px;
    color: white;
    text-align: left;
}

.sec-logo {
    font-size: 18px;
    font-weight: bold;
    color: white;
    text-align: right;
}

```
# OUTPUT:

![alt text](<Screenshot 2025-04-25 141406.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
