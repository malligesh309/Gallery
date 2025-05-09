# Ex.08 Design of Interactive Image Gallery
# Date:09.05.2025
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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>UFC Fighters Gallery</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&family=Playfair+Display:wght@700&family=Quicksand:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Quicksand', sans-serif;
      background: linear-gradient(45deg, #1e1e2f, #3a3a5d);
      background-size: 400% 400%;
      animation: gradientAnimation 15s ease infinite;
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    @keyframes gradientAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin-top: 40px;
      margin-bottom: 20px;
      color: #ffcc00;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 25px;
      max-width: 90%;
      padding: 20px;
    }

    .gallery-item {
      position: relative;
      overflow: hidden;
      border-radius: 12px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.6);
      transition: transform 0.4s ease;
    }

    .gallery-item:hover {
      transform: scale(1.05);
    }

    .gallery-item img {
      width: 100%;
      height: 300px;
      object-fit: cover;
      border-radius: 12px;
    }

    .gallery-item h2 {
      position: absolute;
      bottom: 0;
      margin: 0;
      width: 100%;
      padding: 10px;
      background: rgba(0, 0, 0, 0.7);
      color: #fff;
      font-size: 1.2rem;
      text-align: center;
      font-family: 'Poppins', sans-serif;
    }

    footer {
      margin-top: auto;
      padding: 15px;
      background-color: #111;
      width: 100%;
      text-align: center;
      color: #aaa;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <h1>UFC Fighters Gallery</h1>

  <div class="gallery">
    <div class="gallery-item">
      <img src="C:\Users\MALLIGESH\Documents\grade\image1.jpg" alt="Conor The Notorius Mcregor">
      <h2>Conor The Notorius Mcregor</h2>
    </div>
    <div class="gallery-item">
      <img src="C:\Users\MALLIGESH\Documents\grade\image2.jpg" alt="Khabib The eagle Nurmagomedov">
      <h2>Khabib The eagle Nurmagomedov</h2>
    </div>
    <div class="gallery-item">
      <img src="C:\Users\MALLIGESH\Documents\grade\image3.jpg" alt="Jon bones jones">
      <h2>Jon bones jones</h2>
    </div>
    <div class="gallery-item">
      <img src="C:\Users\MALLIGESH\Documents\grade\image4.jpg" alt="Ales Poaton Pereira ">
      <h2>Alex Poaton Pereira </h2>
    </div>
    <div class="gallery-item">
      <img src="C:\Users\MALLIGESH\Documents\grade\image5.jpg" alt="George The rush St Pierre">
      <h2>George The rush St Pierre</h2>
    </div>
  </div>

  <footer>
    Created by Malligesh - 212223230119
  </footer>

</body>
</html>

```
# OUTPUT:
![Screenshot 2025-05-09 141255](https://github.com/user-attachments/assets/557ff35d-5c19-4901-a478-db5266ff0d1e)
![Screenshot 2025-05-09 141303](https://github.com/user-attachments/assets/cae8c560-16df-45fb-9bb2-6c810b90e2de)
![Screenshot 2025-05-09 141309](https://github.com/user-attachments/assets/7174fc4a-026e-4fe6-a265-492dcef52750)
![Screenshot 2025-05-09 141314](https://github.com/user-attachments/assets/74092e4a-3523-43a4-b68c-ee25af1993ff)
![Screenshot 2025-05-09 141319](https://github.com/user-attachments/assets/6740f6ce-7c5f-4810-984a-54186b98db3d)
![Screenshot 2025-05-09 141324](https://github.com/user-attachments/assets/1e3a0b78-f6bb-4e05-8de3-65eb55a93638)



# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
