<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link
      href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css"
      rel="stylesheet"/>
    
    <title>Document</title>
    <link rel="stylesheet" href="weather.css">
    
  </head>
  <body>
   
    <div class="container">
      <div class="search-box">
        <i class="bx bxs-map"></i>
        <input type="text" placeholder="enter your location" />
        <button class="bx bx-search"></button>
      </div>
      <p class="city-hide">city hide</p>

      <div class="weather-box">
        <div class="box">
          <div class="info-weather">
            <div class="weather">
              <img src="images/cloud.png" alt="img" />
              <p class="temperature">16<span>°C</span></p>
              <p class="decription">Broken Clouds</p>
            </div>
          </div>
        </div>
      </div>
      <div class="weather-details">
        <div class="humidity">
          <i class="bx bx-water"></i>
          <div class="text">
            <div class="info-humidity">
              <span>0%</span>
            </div>
            <p>humidity</p>
          </div>
        </div>
        <div class="wind">
          <i class="bx bx-wind"></i>
          <div class="text">
            <div class="info-wind">
              <span>0Km/h</span>
            </div>
            <p>Wind Speed</p>
          </div>
        </div>
      </div>
      <div class="not-found">
        
      </div>
    </div>
    <script src="weather.js"></script>
  </body>
</html>
