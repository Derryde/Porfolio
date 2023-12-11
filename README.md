function calculateCarbonFootprint() {
    const energy = parseFloat(document.getElementById('energy').value);
    const transportation = parseFloat(document.getElementById('transportation').value);
    const waste = parseFloat(document.getElementById('waste').value);

    const energyEmissionFactor = 0.5;
    const transportationEmissionFactor = 2.0;
    const wasteEmissionFactor = 0.1;

    const energyEmissions = energy * energyEmissionFactor;
    const transportationEmissions = transportation * transportationEmissionFactor;
    const wasteEmissions = waste * wasteEmissionFactor;

    const totalCarbonFootprint = energyEmissions + transportationEmissions + wasteEmissions;

    document.getElementById('carbon-footprint').innerText = `${totalCarbonFootprint.toFixed(2)} kg CO2`;
}











  
