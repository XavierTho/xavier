---
layout: game
title: Conversion Tool
description: A tool to convert stuff
type: tangibles
courses: { week: {week: 3} }
---

### Temperature Conversion

<!-- Input Fahrenheit Temperature -->
<p>
  <label>Fahrenheit</label> <br>
  <input id="inputFahrenheit" type="number" placeholder="Fahrenheit" oninput="temperatureConverter(this.value)" onchange="temperatureConverter(this.value)">
</p>

<!-- Output of Function Below -->
<p>Celsius: <span id="outputCelsius"></span></p>


<!-- Math Conversion of F to C -->
<script>
function temperatureConverter(valNum) {
  valNum = parseFloat(valNum);
  document.getElementById("outputCelsius").innerHTML=(valNum-32)*(5/9);
}
</script>


### Speed Conversion

<!-- Input MPH -->
<p>
  <label>MPH</label> <br>
  <input id="inputMPH" type="number" placeholder="MPH" oninput="speedConverter(this.value)" onchange="speedConverter(this.value)">
</p>

<!-- Output of Function Below -->
<p>KPH: <span id="outputKPH"></span></p>

<!-- Math Conversion from MPH to KPH -->
<script>
function speedConverter(valNum) {
  valNum = parseFloat(valNum);
  document.getElementById("outputKPH").innerHTML=(valNum*1.609344);
}
</script>


<!-- Reference: https://www.w3schools.com/howto/howto_js_speed_converter.asp -->