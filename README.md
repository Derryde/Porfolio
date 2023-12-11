function calculateCarbonFootprint() {

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Sustainable Building Calculator</title>
</head>
<body>
    <div class="calculator-container">
        <h1>Sustainable Building Calculator</h1>
        <form id="calculator-form">
            <label for="energy">Energy Consumption (kWh):</label>
            <input type="number" id="energy" required>

            <label for="transportation">Transportation (miles):</label>
            <input type="number" id="transportation" required>

            <label for="waste">Waste Generation (kg):</label>
            <input type="number" id="waste" required>

            <button type="button" onclick="calculateCarbonFootprint()">Calculate</button>
        </form>

        <div id="result-container">
            <h2>Carbon Footprint Result:</h2>
            <p id="carbon-footprint">-</p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>













}











  
