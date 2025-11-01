<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Micro:bit Tilt Test</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #111;
      color: #0f0;
      margin-top: 60px;
    }
    button {
      background: #0f0;
      color: #111;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      border-radius: 6px;
      cursor: pointer;
    }
    .data {
      font-size: 24px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1>Micro:bit Tilt Test</h1>
  <p>Click the button below to connect your micro:bit:</p>
  <button id="connectBtn">🔗 Connect Micro:bit</button>

  <div class="data" id="output">No data yet...</div>

  <script>
    let device;

    document.getElementById('connectBtn').addEventListener('click', async () => {
      try {
        console.log("Requesting device...");
        device = await navigator.bluetooth.requestDevice({
          filters: [{ namePrefix: "BBC micro:bit" }],
          optionalServices: [0xFFE0, 0xFFE1, "0000ffe5-0000-1000-8000-00805f9b34fb"]
        });
        const server = await device.gatt.connect();
        document.getElementById('output').textContent = "✅ Connected to " + device.name;

        // Example: pretend we're receiving tilt data
        // In real code you'd read from a characteristic here
        setInterval(() => {
          const randomTilt = ["Left", "Right", "Up", "Down", "Flat"][Math.floor(Math.random() * 5)];
          document.getElementById('output').textContent = "Tilt: " + randomTilt;
        }, 1000);
      } catch (error) {
        console.error(error);
        document.getElementById('output').textContent = "❌ Error: " + error.message;
      }
    });
  </script>
</body>
</html>
