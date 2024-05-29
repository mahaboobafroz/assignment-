
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vehicle Transport Converter</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Vehicle Transport Converter</h1>
        <div class="input-section">
            <label for="distance">Enter Distance (km):</label>
            <input type="number" id="distance" name="distance">
        </div>
        <div class="vehicle-selection">
            <h3>Select Vehicle Type:</h3>
            <form id="vehicle-form">
                <input type="radio" id="alto" name="vehicle" value="alto">
                <label for="alto">Maruti Suzuki Alto</label><br>
                <input type="radio" id="i20" name="vehicle" value="i20">
                <label for="i20">Hyundai i20</label><br>
                <input type="radio" id="nexon" name="vehicle" value="nexon">
                <label for="nexon">Tata Nexon</label><br>
                <input type="radio" id="city" name="vehicle" value="city">
                <label for="city">Honda City</label><br>
                <input type="radio" id="thar" name="vehicle" value="thar">
                <label for="thar">Mahindra Thar</label><br>
                <input type="radio" id="innova" name="vehicle" value="innova">
                <label for="innova">Toyota Innova Crysta</label><br>
                <input type="radio" id="seltos" name="vehicle" value="seltos">
                <label for="seltos">Kia Seltos</label><br>
                <input type="radio" id="kwid" name="vehicle" value="kwid">
                <label for="kwid">Renault Kwid</label><br>
                <input type="radio" id="ecosport" name="vehicle" value="ecosport">
                <label for="ecosport">Ford EcoSport</label><br>
                <input type="radio" id="tiago" name="vehicle" value="tiago">
                <label for="tiago">Tata Tiago</label><br>
            </form>
        </div>
        <button onclick="calculate()">Calculate</button>
        <div id="results" class="results-section"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
