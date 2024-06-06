<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora de Dosis</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="calculator">
        <h2>Calculadora de Dosis</h2>

        <!-- Sección para calcular el porcentaje de variación de dosis -->
        <div class="section">
            <h3>Porcentaje de Variación de Dosis</h3>
            <div>
                <label for="original-dose1">Dosis Original:</label>
                <input type="number" id="original-dose1">
            </div>
            <div>
                <label for="final-dose1">Dosis Final:</label>
                <input type="number" id="final-dose1">
            </div>
            <button onclick="calculatePercentageChange()">Calcular Porcentaje</button>
            <div id="result1"></div>
        </div>

        <!-- Sección para calcular la dosis final basada en un porcentaje de cambio -->
        <div class="section">
            <h3>Dosis Final con Porcentaje de Cambio</h3>
            <div>
                <label for="original-dose2">Dosis Original:</label>
                <input type="number" id="original-dose2">
            </div>
            <div>
                <label for="percent-change">Porcentaje de Cambio:</label>
                <input type="number" id="percent-change">
            </div>
            <button onclick="calculateFinalDose()">Calcular Dosis Final</button>
            <div id="result2"></div>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
# calculadora-dosis
