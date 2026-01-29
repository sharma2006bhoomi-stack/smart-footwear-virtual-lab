# smart-footwear-virtual-lab
Virtual Lab for simulated comfort, pressure and thermal analysis of footwear soles
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Smart Footwear Virtual Lab</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      margin: 0;
      padding: 0;
    }
    header {
      background: #1f3c88;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      background: white;
      margin: 20px;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    h2 {
      color: #1f3c88;
    }
    .placeholder {
      color: gray;
      font-style: italic;
    }
  </style>
</head>

<body>

<header>
  <h1>Smart Footwear Virtual Lab</h1>
  <p>Virtual simulation of pressure & thermal comfort in footwear</p>
</header>

<section>
  <h2>1. Introduction</h2>
  <p class="placeholder">Project overview will come here...</p>
</section>

<section>
  <h2>2. Theory Background</h2>
  <p class="placeholder">Pressure distribution and thermal theory...</p>
</section>

<section>
  <h2>3. User Input Parameters</h2>

  <label><b>User Weight (kg)</b></label><br>
  <input type="range" id="weight" min="50" max="120" value="70"
         oninput="document.getElementById('wval').innerText=this.value">
  <span id="wval">70</span> kg
  <br><br>

  <label><b>Outside Temperature (°C)</b></label><br>
  <input type="range" id="temp" min="15" max="45" value="30"
         oninput="document.getElementById('tval').innerText=this.value">
  <span id="tval">30</span> °C
  <br><br>

  <button disabled>Run Simulation</button>
</section>


<section>
  <h2>4. Virtual Simulation Output</h2>
  <p class="placeholder">Pressure & heat results will appear here...</p>
</section>

<section>
  <h2>5. Conclusion</h2>
  <p class="placeholder">Final observations and learning outcomes...</p>
</section>
<script>
const slider = document.getElementById("weightSlider");
const output = document.getElementById("weightValue");

slider.addEventListener("input", function () {
  output.innerText = slider.value;
});
</script>
</body>
</html>
