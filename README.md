# Ex.06 Book Front Cover Page Design
# Date:06-10-2025
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
  <title>Book Cover</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: #e0e0e0;
      font-family: 'Georgia', serif;
    }

    .cover {
      width: 400px;
      height: 600px;
      background: url('https://picsum.photos/400/600?grayscale') no-repeat center/cover;
      box-shadow: 0 10px 20px rgba(0,0,0,0.4);
      position: relative;
      border-radius: 10px;
      overflow: hidden;
    }

    
    .overlay {
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.5);
    }

    
    .title {
      position: absolute;
      top: 20%;
      width: 100%;
      text-align: center;
      font-size: 2.5rem;
      font-weight: bold;
      color: #2a0b9a;
      letter-spacing: 2px;
    }

    
    .subtitle {
      position: absolute;
      top: 35%;
      width: 100%;
      text-align: center;
      font-size: 1.8rem;
      color: #ddd;
      font-style: italic;
    }

    
    .author {
      position: absolute;
      bottom: 10%;
      width: 100%;
      text-align: center;
      font-size: 2rem;
      font-weight: bold;
      color: #a00606;
    }

    
    .photo {
      position: absolute;
      bottom: 25%;
      left: 50%;
      transform: translateX(-50%);
      width: 120px;
      height: 120px;
    }
  </style>
</head>
<body>
  <div class="cover">
    <div class="overlay"></div>
    <div class="title">THE SPIRIT OF MUSIC</div>
    <div class="subtitle">Unfolding the Magic of Melody</div>
    <div class="photo"></div>
    <img src="A R Rahman.jpeg"></div>
    <div class="author">By AR Rahman</div>
  </div>
</body>
</html>


```
# OUTPUT:
![alt text](<Screenshot 2025-10-06 212716.png>)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
