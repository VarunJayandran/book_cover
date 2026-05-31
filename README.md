# Ex.05 Book Front Cover Page Design
# Date:31-05-2026
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
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      background: #0ac5af;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: #343232;
      position: relative;
      padding: 30px;
      box-sizing: border-box;
      border-radius: 10px;
      overflow: hidden;
    }

    .expert {
      font-size: 14px;
      text-transform: uppercase;
      border-bottom: 2px solid orange;
      display: inline-block;
      margin-bottom: 20px;
    }

    .title {
      font-size: 32px;
      font-weight: bold;
      line-height: 1.3;
      margin-bottom: 20px;
    }

    .subtitle {
      font-size: 16px;
      margin-bottom: 40px;
    }

    .wave {
      position: absolute;
      bottom: 100px;
      left: 0;
      width: 100%;
      height: 120px;
      background: url('https://svgshare.com/i/16xz.svg') no-repeat center;
      background-size: cover;
      opacity: 0.7;
    }

    .edition {
      font-size: 18px;
      color: orange;
      font-weight: bold;
      position: absolute;
      bottom: 60px;
      left: 30px;
    }

    .author {
      position: absolute;
      bottom: 10px;
      right: 20px;
      text-align: right;
    }

    .author img {
      width: 80px;
      height: 80px;
      border-radius: 5%;
    }

    .author-name {
      margin-top: 5px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="expert">Expert Insight</div>
    <div class="title">A BRIEF<br>HISTORY <br>OF TIME</div>
    <div class="subtitle">However difficult life may seem,<br>there is always something you can do and succeed at !</div>
    <div class="wave"></div>
    <div class="edition"></div>
    <div class="author">
    <img src="/static/stephen.jpg">
    <div class="author-name">Stephen Hawkin</div> 
    </div>
```
# OUTPUT:
<img width="1919" height="1092" alt="image" src="https://github.com/user-attachments/assets/02d4124f-a486-4d1e-8c3c-74116cc1f019" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
