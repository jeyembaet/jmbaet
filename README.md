<!doctype html>
<html> 
 <head> 
  <title>Simple Portfolio</title> 
  <link rel="stylesheet" href="styles.css"> <!-- Add this new CSS for the logo --> 
  <style>
    .anime-logo {
      display: block;
      margin: 0 auto 20px auto;
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 2px solid #0f0;
      box-shadow: 0 0 15px rgba(0, 255, 0, 0.3);
    }
    
    h1 {
      margin-top: 20px;
    }
  </style> 
 </head> 
 <body> 
  <div class="container"> 
   <img src="your-logo.png" class="anime-logo" alt="Anime Logo"> <!-- Replace with your actual image file --> 
   <h1>My Portfolio</h1> 
  </div> 
  <div class="container"> 
   <section> 
    <h2>About Me</h2> 
    <p>I'm John Mark C Baet</p> 
    <p>2nd yr IT Student</p> 
   </section> 
  </div> 
  <div class="container"> 
   <section> 
    <h2>Projects</h2> 
    <p>Project 1: Inventory System.</p> 
    <p>Project 2: Networking System.</p> 

body {
  font-family: sans-serif;
  margin: 100px;
  font-size: 18px;
  color: #0f0; 
  position: relative;
  overflow: hidden; 
  background-color: #000;
}

/* Animated background effect */
body::before {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: 
    repeating-linear-gradient(
      0deg,
      rgba(0, 255, 0, 0.1) 0px,
      rgba(0, 255, 0, 0.1) 1px,
      transparent 1px,
      transparent 20px
    ),
    repeating-linear-gradient(
      90deg,
      rgba(0, 255, 0, 0.1) 0px,
      rgba(0, 255, 0, 0.1) 1px,
      transparent 1px,
      transparent 20px
    );
  background-size: 20px 20px;
  animation: gridScroll 50s linear infinite;
  z-index: -2;
}

@keyframes gridScroll {
  from { background-position: 0 0; }
  to { background-position: 0 1000px; }
}

/* Matrix-like rain effect overlay */
body::after {
  content: "";
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(
    to bottom,
    rgba(0, 0, 0, 0.9) 10%,
    rgba(0, 255, 0, 0.1) 50%,
    rgba(0, 0, 0, 0.9) 90%
  );
  animation: scan 6s linear infinite;
  pointer-events: none;
  z-index: -1;
}

@keyframes scan {
  0% { background-position: 0 -100%; }
  100% { background-position: 0 100%; }
}

.container {
  max-width: 800px;
  margin: 20px auto;
  padding: 20px;
  background-color: rgba(0, 20, 0, 0.9);
  border-radius: 4px;
  box-shadow: 0 0 20px rgba(0, 255, 0, 0.2);
  border: 1px solid rgba(0, 255, 0, 0.1);
  position: relative;
  backdrop-filter: blur(2px);
}

h1 {
  text-align: center;
  color: #0f0;
  text-shadow: 0 0 10px #0f0;
  margin-bottom: 30px;
}

h2 {
  color: #0f0;
  border-bottom: 1px solid rgba(0, 255, 0, 0.3);
  padding-bottom: 5px;
}    
   </section> 
  </div> 
  <div class="container"> 
   <section> 
    <h2>Contact</h2> 
    <p>Email: baetjm74@gmail.com</p> 
   </section> 
  </div> 
 </body>
</html>
