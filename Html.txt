<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Weather App</title>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Weather App</h1>
            <div id="location"></div>
            <div id="date"></div>
        </div>
        <div class="search-container">
            <input type="text" id="cityInput" placeholder="Enter city name or ZIP code">
            <button onclick="getWeather()">Search</button>
        </div>
        <div id="weatherInfo"></div>
    </div>

    <script src="script.js"></script>
</body>
</html>
