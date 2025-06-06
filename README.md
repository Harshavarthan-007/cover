# Ex.06 Book Front Cover Page Design
## Date:20/05/25

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
  <title>Marie Curie Book Cover</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: linear-gradient(135deg, #e0f7fa, #80deea);
    }

    .book-cover {
      width: 320px;
      height: 480px;
      background: linear-gradient(145deg, #004d40, #006064);
      border-radius: 16px;
      padding: 25px 20px;
      box-shadow: 0 12px 25px rgba(0, 0, 0, 0.5);
      position: relative;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    .title {
      font-family: 'Playfair Display', serif;
      font-size: 1.9rem;
      font-weight: bold;
      margin-bottom: 15px;
    }

    .subtitle {
      font-size: 1.05rem;
      font-style: italic;
      margin-bottom: 20px;
      color: #b2ebf2;
    }

    .author {
      font-size: 1rem;
      margin-top: 10px;
      font-style: italic;
      color: #e0f2f1;
    }

    .curie-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid #fff;
      box-shadow: 0 0 15px #00bcd4;
      margin-bottom: 15px;
      object-fit: cover;
    }

    .author-photo-container {
      position: absolute;
      bottom: 10px;
      right: 10px;
      text-align: center;
    }

    .author-photo {
      width: 60px;
      height: 80px;
      border: 2px solid #fff;
      border-radius: 8px;
      object-fit: cover;
      box-shadow: 0 4px 10px rgba(255, 255, 255, 0.3);
    }

    .credit {
      font-size: 0.7rem;
      color: #b2dfdb;
      margin-top: 4px;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="title">Marie Curie: A Radiant Legacy</div>
    <img src="marie.webp" alt="Marie Curie" class="curie-img">
    <div class="subtitle">Discovering brilliance through science</div>
    <div class="author">by Marie Curie</div>

    <!-- Your Photo in Bottom-Right with Caption -->
    <div class="author-photo-container">
      <img src="aaya.webp" alt="Designed by Dhoni" class="author-photo">
      <div class="credit">Designed by Dhoni</div>
    </div>
  </div>
</body>
</html>
```

## OUTPUT:
![alt text](image.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
