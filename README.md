# Ex09 Event Registration Web Application
## Date:9-11-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Drestien 2025 - One Piece Registration</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #000;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .screen {
      display: none;
      width: 390px;
      height: 844px;
      border-radius: 20px;
      overflow: hidden;
      position: relative;
      background-color: #fff;
      color: #000;
    }

    .active {
      display: block;
    }

    /* Landing Screen */
    #screen1 {
      background: url('https://i.ibb.co/wBWDQZz/onepiece-bg.jpg') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 30px 20px;
    }

    #screen1 h1 {
      font-size: 2rem;
      margin-top: 60%;
    }

    #screen1 button {
      margin-top: 20px;
      background: #ffcc00;
      color: #000;
      padding: 12px 25px;
      border: none;
      border-radius: 10px;
      font-weight: bold;
      cursor: pointer;
    }

    /* Registration Screens */
    .form {
      background: url('https://i.ibb.co/8Dg4d6h/onepiece-pattern.jpg') center/cover;
      height: 100%;
      padding: 50px 30px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .form input {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 8px;
      border: none;
      text-align: center;
      font-size: 1rem;
    }

    .form button {
      margin-top: 20px;
      background: #ffcc00;
      color: #000;
      padding: 12px 30px;
      border: none;
      border-radius: 8px;
      font-weight: bold;
      cursor: pointer;
    }

    /* Thank You Screen */
    #screen4 {
      background: #000;
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    #screen4 img {
      width: 100%;
      margin-top: 20px;
      border-radius: 12px;
    }

    #screen4 h2 {
      color: #ffcc00;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <!-- Screen 1: Landing -->
  <div class="screen active" id="screen1">
    <h1>DRESTIEN 2025</h1>
    <p>SAVEETHA ENGINEERING COLLEGE PRESENTS<br><b>THE ONE PIECE HUNT FOR THE TREASURE</b></p>
    <button onclick="nextScreen(2)">BOOK NOW</button>
  </div>

  <!-- Screen 2: Registration Part 1 -->
  <div class="screen" id="screen2">
    <div class="form">
      <input type="text" id="name" placeholder="NAME" required>
      <input type="text" id="year" placeholder="YEAR" required>
      <input type="text" id="college" placeholder="COLLEGE" required>
      <input type="text" id="mobile" placeholder="MOBILE NO" required>
      <button onclick="nextScreen(3)">NEXT</button>
    </div>
  </div>

  <!-- Screen 3: Registration Part 2 -->
  <div class="screen" id="screen3">
    <div class="form">
      <input type="text" id="members" placeholder="NO OF MEMBERS" required>
      <input type="text" id="team" placeholder="TEAM NAME" required>
      <input type="email" id="email" placeholder="EMAIL" required>
      <button onclick="nextScreen(4)">SUBMIT</button>
    </div>
  </div>

  <!-- Screen 4: Thank You -->
  <div class="screen" id="screen4">
    <h2>THANK YOU FOR REGISTRATION</h2>
    <p>We are eagerly waiting for you to participate in the event!<br>
      All the best for you and your team!</p>
    <p style="margin-top:20px;">For more details, contact the student or staff coordinator.</p>
    <img src="https://i.ibb.co/VW3ytBg/onepiece-crew.jpg" alt="One Piece Crew">
  </div>

  <script>
    function nextScreen(screenNumber) {
      document.querySelectorAll('.screen').forEach(s => s.classList.remove('active'));
      document.getElementById(`screen${screenNumber}`).classList.add('active');
    }
  </script>
</body>
</html>

```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-11-10 114447" src="https://github.com/user-attachments/assets/df2eefd1-2087-4f24-893a-d0d739951437" />

click here to view prototype 🔻

https://www.figma.com/proto/XftENAtZnmOMCwPmIQxujk/Untitled?node-id=0-1&t=TDhU7793cL9ifVzN-1

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
