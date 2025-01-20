# HarvestGuard-69-SUSTAIN-AI-THON
# Brief Intro
HarvestGuard is a smart agricultural platform that enables knowledge sharing among farmers, a direct farmer-to-consumer marketplace, and AI-powered weather insights. It provides real-time crop advisory, smart pest alerts, AI-based price predictions, and blockchain-secured transactions to ensure fair trade.
# WorkFlow Diagram
[![Image](https://github.com/user-attachments/assets/c39fec73-7c31-40eb-8336-83f2ee080099)](url)
# Concept Map
[![Image](https://github.com/user-attachments/assets/96105fc1-438c-49c7-90f6-025bdeab32b3)](url)
# Tech stack
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HarvestGuard</title>
    <link rel="stylesheet" href="index.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
</head>
<body>
    <nav>
        <h2>Harvest<span style="color: chocolate;">Guard</span></h2>
        <div class="navbar">
        <a href="#">Home</a>
        <a href="#">About us</a>
        <a href="#">Market Place</a>
        <a href="consumerlogin.html">Login</a>
        </div>
    </nav>
    <div class="Body">
        <div class="body-content">
        <img src="farmer-removebg-preview.png" width="550px">
        <div class="contents">
        <h1>Harvest<span style="color: chocolate;">Guard</span></h1>
        <p>HarvestGuard is a smart agricultural platform that enables knowledge sharing among farmers,a direct farmer-to-consumer marketplace, and AI-powered weather insights.</p>
       <div class="button1">
        <button>See More</button>
        <button>See More</button>
        </div>
        </div>
        </div>
    </div>
    <div class="content2">
       <div class="content-box">
        <p>Build Connection, Share Knowledge and Collaborate on Best Practices</p>
       </div> 
       <div class="content-box">
        <p>Direct Connection Between Farmers and Consumers</p>
       </div> 
       <div class="content-box">
        <p>Sustainable Farming Practices and Reduce Food Wastage</p>
       </div> 
    </div>

</body>
</html>
body{
    margin: 0px;
    padding: 0px;
    font-family: "Poppins", serif;
    height: 100%;
}
nav{
    display: flex;
    justify-content: space-between;
    background-color: green;
    z-index: 10;
}
.navbar{
    display: flex;
    justify-content: space-between;
    column-gap: 25px;
    align-items: center;
    z-index: 10;
}
nav h2{
    margin-left: 10px;
}
.navbar a{
    text-decoration: none;
    color: black;
    margin-right: 10px;
}
.navbar a{
    text-decoration: none;
    color: black;
    margin-right: 10px;
}
.navbar a:hover{
    text-decoration: underline;
}
.Body{
    height: 515px; 
    background-image: url('pexels-pixabay-325944.jpg');
    background-size: cover;
    background-position: center;
    overflow: hidden;
    opacity: 0.9;
    position: relative;
    z-index: 10;
}
.body-content img{
    position: absolute;
    top: -10px;
    right:-80px;
    z-index:1;
    opacity: 1;
    
}
.body-content{
    display: flex;
    flex-direction: row;
 justify-content: space-between;
}
.contents h1{
    position: relative;
    top:20px;
}
.contents{
    position: absolute;
    top:60px;
    left:60px;
    display: flex;
    flex-direction: column;
    width:500px;
}
.contents p{
    font-weight: 500;
    color:white;
    font-size: 20px;
}
.contents button{
    padding: 10px;
    border-radius: 20px;
    width:100px;
    border-color: black;
    border-top-color: black;
    border-left-color: black;
    border-bottom-color: black;
    background-color: green;
}
.button1{
    display: flex;
    flex-direction: row;
}
.content2{
    height: 100vh;
    background-image: url('sunny-meadow-landscape.jpg');
    background-size: cover;
    display: flex;
    justify-content:center;
    align-items:center;
    flex-direction: column;
    row-gap: 20px;
}
.content-box{
    width: 500px;
    height: 100px;
    background-color: white;
    border-radius: 20px;
    background-color: rgba(255, 255, 255, 0.372);
    backdrop-filter: blur(10px);

}
.content-box p{
    margin-left: 20px;
    font-size: 20px;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Content</title>
    <style>
        /* CSS Styling */
        .weather-content {
            text-align: center;
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        .weather-content a img {
            border-radius: 50%; /* Makes the image circular */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .weather-content a img:hover {
            transform: scale(1.1); /* Adds a zoom effect on hover */
        }

        .weather-content h1 {
            color: #4CAF50;
            font-size: 2em;
            margin: 10px 0;
        }

       .weather-box {
            background-color: #f4f4f4;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            display: inline-block;
        }

        .weather-box h1 {
            font-size: 1.5em;
            color: #333;
            margin: 0;
        }

        .weather-box h3 {
            font-size: 1em;
            color: #666;
            margin: 5px 0;
        }

        .weather-box .temperature {
            font-size: 1.2em;
            color: #FF5733;
            margin-top: 10px;
            font-weight: bold;
        }

        .img-box img {
            border-radius: 10px; /* Adds rounded corners to the image */
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="weather-content">
        <a href="https://www.accuweather.com/en/in/india-weather">
            <img src="pngwing.com.png" width="150px" height="150px" alt="Weather Icon">
        </a>
        <h1>Trust The Cloud,<br>Know The Weather!</h1>
        <div class="weather-box">
            <h1>Chengalpattu</h1>
            <h3>India</h3>
            <div class="temperature">75°F</div>
            <div class="img-box">
                <img src="vecteezy_3d-render-cloudy-night-weather-front-view_11300017.png" 
                     width="100px" height="100px" alt="Weather Condition">
            </div>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Customer Login</title>
  <link rel="stylesheet" href="styl1e.css">
</head>
<body>
  <div class="login-box">
    <div class="box">
      <h1>Consumer Login</h1>
      <form>
        <label for="email">Email</label>
        <input type="email" id="email" placeholder="Enter your email" required>
        <label for="password">Password</label>
        <input type="password" id="password" placeholder="Enter your password" required>
        <button type="submit">Login</button>
      </form>
    </div>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Customer Login</title>
  <link rel="stylesheet" href="styl1e.css">
  <style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Poppins", sans-serif;
  }
  
  /* Background Styling */
  .login-box {
    height: 100vh;
    background-image: url('sunny-meadow-landscape.jpg'); /* Add your image path */
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
   align-items: center;
  }
  
  /* Login Box Styling */
  .box {
    width: 400px;
    padding: 40px 20px;
    background-color: rgba(255, 255, 255, 0.8);
    backdrop-filter: blur(10px);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
    border-radius: 20px;
    background-color: rgba(255, 255, 255, 0.372);
    backdrop-filter: blur(10px);
  }
  
  .box h1 {
    margin-bottom: 20px;
    font-size: 24px;
    color: #333;
  }
  
  /* Form Styling */
  .box form {
    display: flex;
    flex-direction: column;
    gap: 15px;
  }
 .box label {
    font-size: 14px;
    color: #555;
    text-align: left;
  }
  
  .box input {
    width: 100%;
    padding: 10px 15px;
    font-size: 16px;
    border: 1px solid #ddd;
    border-radius: 8px;
    outline: none;
    transition: border-color 0.3s ease;
  }
  
  .box input:focus {
    border-color: #4CAF50;
  }
  
  .box button {
    padding: 10px 15px;
    font-size: 16px;
    color: #fff;
    background-color: #4CAF50;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: background-color 0.3s ease;
  }
 .box button:hover {
    background-color: #45a049;
  }
  .button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #4CAF50;
    color: white;
    text-align: center;
    text-decoration: none;
    border-radius: 5px;
    font-size: 16px;
}

.button:hover {
    background-color: #45a049;
}

  
  </style>
</head>
<body>
  <div class="login-box">
    <div class="box">
      <h1>Farmer Login</h1>
      <form>
        <label for="email">Email</label>
        <input type="email" id="email" placeholder="Enter your email" required>
        <label for="password">Password</label>
        <input type="password" id="password" placeholder="Enter your password" required>
        <a href="weather.html" class="button">Login</a>
      </form>
    </div>
  </div>
</body>
</html>
# Novelty
HarvestGuard innovates by integrating AI-powered crop advisory, weather insights, blockchain-secured transactions, and a direct farmer-to-consumer marketplace into one platform. It promotes sustainable farming, reduces intermediaries, and ensures fair pricing. With community-driven knowledge sharing, logistics support, and easy access to government schemes, HarvestGuard transforms agriculture into a more profitable, efficient, and sustainable practice for farmers worldwide.
# Solution

