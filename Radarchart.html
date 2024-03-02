<!DOCTYPE html>
<html>
<head>
    <title>Radar Chart Generator</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }
        input {
            margin: 10px;
            padding: 5px;
            width: 50px;
        }
        canvas {
            margin-top: 20px;
            border: 1px solid #ddd;
        }
        button {
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #555;
        }
        #qrcode {
            text-align: center;
            margin-top: 20px;
        }
        #qrcode img {
            width: 128px;
            height: 128px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Radar Chart Generator</h1>
    </header>
    <div class="container">
        <label for="input1">Input 1:</label>
        <input type="number" id="input1" value="0" min="0" max="100"><br>
        <label for="input2">Input 2:</label>
        <input type="number" id="input2" value="0" min="0" max="100"><br>
        <label for="input3">Input 3:</label>
        <input type="number" id="input3" value="0" min="0" max="100"><br>
        <label for="input4">Input 4:</label>
        <input type="number" id="input4" value="0" min="0" max="100"><br>
        <button onclick="generateRadarChart()">Generate Radar Chart</button>
        <canvas id="radarChart" width="400" height="400"></canvas>
        <div id="qrcode"></div>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/qrcode@1.4.4/qrcode.min.js"></script>
    <script>
        function generateRadarChart() {
            const canvas = document.getElementById('radarChart');
            const ctx = canvas.getContext('2d');

            const data = {
                labels: ['Input 1', 'Input 2', 'Input 3', 'Input 4'],
                datasets: [{
                    label: 'Values',
                    data: [
                        parseInt(document.getElementById('input1').value),
                        parseInt(document.getElementById('input2').value),
                        parseInt(document.getElementById('input3').value),
                        parseInt(document.getElementById('input4').value)
                    ],
                    backgroundColor: 'rgba(255, 99, 132, 0.2)',
                    borderColor: 'rgba(255, 99, 132, 1)',
                    borderWidth: 1
                }]
            };

            const options = {
                scale: {
                    ticks: {
                        beginAtZero: true,
                        min: 0,
                        max: 100,
                        stepSize: 20
                    }
                }
            };

            new Chart(ctx, {
                type: 'radar',
                data: data,
                options: options
            });

            const qrCodeDiv = document.getElementById('qrcode');
            qrCodeDiv.innerHTML = ''; // Clear previous QR code
            const qr = new QRCode(qrCodeDiv, {
                text: window.location.href, // Link to the current page
                width: 128,
                height: 128
            });
        }
    </script>
</body>
</html>
