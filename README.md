<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">


  

  <h1>🌦️ Weather Dashboard</h1>

  <div class="section">
    <h2>🎯 Project Objective</h2>
    <p>
      The objective of this project is to create an interactive dashboard to analyze weather data 
      (🌡️ temperatures, 💨 wind speed, ☔ precipitation, 🔽 air pressure), 
      providing insights into weather patterns across seasons and years.
    </p>
  </div>

  <div class="section">
    <h2>📊 Dataset Used</h2>
    <p>
      The dashboard uses weather data for 2024 and 2025:  
      <br>🌡️ Maximum and minimum temperatures  
      💨 Wind speed  
      🔽 Air pressure  
      ☔ Daily and monthly precipitation  
    </p>
  </div>

  <div class="section">
    <h2>❓ Questions Addressed</h2>
    <ul>
      <li>What are the maximum and minimum temperatures during the day and night?</li>
      <li>What is the highest recorded wind speed?</li>
      <li>What percentage of precipitation in 2025 compared to the combined total of 2024 and 2025?  
        <span class="highlight">☔ 63%</span>
      </li>
      <li>How is air pressure and precipitation distributed by wind direction?</li>
      <li>How have temperature, wind speed and precipitation changed over months and years?</li>
    </ul>
  </div>

  <div class="section">
    <h2>📝 How the 63% Precipitation Was Calculated</h2>
    <p>
      Percentage (%) = (Total Precipitation in 2025 ÷ (Total Precipitation in 2024 + Total Precipitation in 2025)) × 100  
      <br>Example: (315 ÷ (185 + 315)) × 100 = <span class="highlight">63%</span>
    </p>
    <p>
      This percentage was built using <strong>Deneb</strong> with a dynamic gradient that visually moves to represent the proportion.
    </p>
  </div>

  <div class="section">
    <h2>🛠️ Process for Analyzing the Dashboard and Identifying KPIs</h2>
    <ul>
      <li>Understand the context and overall purpose of the dashboard to grasp what data is presented.</li>
      <li>Identify key metrics such as maximum temperatures, wind speed, and precipitation.</li>
      <li>Connect each chart or metric to the question it answers.</li>
      <li>Analyze patterns and trends using visuals and timelines.</li>
      <li>Summarize findings to highlight key performance indicators and actionable insights.</li>
    </ul>
  </div>

  <div class="section">
    <h2>🚀 Steps Taken</h2>
    <ul>
      <li>Collected weather data from open sources or APIs.</li>
      <li>Stored and processed the data using SQL or Power Query.</li>
      <li>Created advanced calculations using DAX (including the 63% precipitation measure).</li>
      <li>Built interactive visuals in Power BI using <strong>Deneb</strong> with a moving gradient for the percentage display.</li>
      <li>Designed a responsive interface with HTML and CSS.</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚡ Challenges & Solutions</h2>
    <ul>
      <li>Handling incomplete or missing data → used data cleaning and imputation techniques.</li>
      <li>Creating an appealing interface → used consistent colors and weather emojis/icons.</li>
      <li>Implementing a dynamic percentage visualization → used Deneb gradient animations.</li>
    </ul>
  </div>

  <div class="section">
    <h2>💡 Recommendations to Improve Performance</h2>
    <ul>
      <li>⭐ Focus on peak weather months  
        <br>Align decisions or campaigns with months of significant weather changes.</li>
      <li>📈 Analyze yearly trends  
        <br>Compare 2024 and 2025 to identify patterns.</li>
      <li>⚡ Study wind direction impact on air pressure and precipitation  
        <br>Helps improve forecasting and planning.</li>
    </ul>
  </div>

</body>
</html>
