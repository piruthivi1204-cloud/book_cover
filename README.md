# Ex.06 Book Front Cover Page Design
# Date:05/10/25
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
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #ffdd00;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgb(84, 6, 32);
      border: 2px solid hsl(61, 100%, 84%);
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(49, 55, 49, 0.751);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
        padding: 10px;
      font-size: 28px;
      font-weight: bold;
      color: #f3e227;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
        padding: 10px;
        color: #ffffff;
        font-size: 16px;
        margin-top: 10px;
        text-align: center;
        font-style: italic;
    }

    .image {
        padding-top: 60px;
      flex: 1;
      margin: auto;
      background: url('https://upload.wikimedia.org/wikipedia/commons/6/65/Simple_flowers_black_line_art.png') center/contain no-repeat;
      margin: 30px 0;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #edda30;
      margin-top: 20px;
    }

    .line {
      height: 2px;
      background: #ef4545;
      width: 50px;
      margin: 10px auto;
      
    }
  </style>
</head>
<body>
   
  <div class="book-cover">
    <div>
      <div class="title">Fundamental of Web application</div>
      <div class="line"></div>
      <div class="subtitle">Full stack development</div>
    </div>
    <div class="image">
      
            <center><img src="pirupa.png" length="500" width="300"></center>
    </div>
    <div class="author">By Zendaya</div>
  </div>
</body>
</html>
```
# OUTPUT:
![alt text](<Screenshot 2025-10-05 224057.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
