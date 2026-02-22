<h1 align="center">🚔 Crime Data Analysis & Pattern Insights</h1>

<p align="center">
  <strong>بسم الله الرحمن الرحيم</strong><br>
  <em>And my success is only by Allah</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas">
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy">
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange">
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-green">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project explores and analyzes crime incident data to uncover temporal patterns,
geographical trends, and demographic insights using Python-based data analysis tools.
</p>

<ul>
  <li>🕒 Crime frequency by hour</li>
  <li>🌙 Night crime hotspot detection</li>
  <li>👥 Victim age distribution analysis</li>
  <li>📊 Data cleaning & feature engineering</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>

<ul>
  <li><strong>Python</strong></li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
</ul>

<hr>

<h2>📂 Dataset Overview</h2>

<p>
The dataset contains <strong>185,715 crime records</strong> with the following key attributes:
</p>

<table>
  <tr>
    <th>Column</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>DR_NO</td>
    <td>Unique crime report number</td>
  </tr>
  <tr>
    <td>Date Rptd</td>
    <td>Date reported</td>
  </tr>
  <tr>
    <td>DATE OCC</td>
    <td>Date occurred</td>
  </tr>
  <tr>
    <td>TIME OCC</td>
    <td>Time occurred (HHMM format)</td>
  </tr>
  <tr>
    <td>AREA NAME</td>
    <td>Geographical division of crime</td>
  </tr>
  <tr>
    <td>Crm Cd Desc</td>
    <td>Crime description</td>
  </tr>
  <tr>
    <td>Vict Age</td>
    <td>Victim age</td>
  </tr>
  <tr>
    <td>Vict Sex</td>
    <td>Victim gender</td>
  </tr>
  <tr>
    <td>Vict Descent</td>
    <td>Victim ethnicity</td>
  </tr>
  <tr>
    <td>Weapon Desc</td>
    <td>Weapon used (if applicable)</td>
  </tr>
  <tr>
    <td>Status Desc</td>
    <td>Case status</td>
  </tr>
  <tr>
    <td>LOCATION</td>
    <td>Crime location</td>
  </tr>
</table>

<hr>

<h2>🧹 Data Preparation</h2>

<ul>
  <li>✔ Parsed <code>Date Rptd</code> and <code>DATE OCC</code> into datetime format</li>
  <li>✔ Extracted hour from <code>TIME OCC</code></li>
  <li>✔ Created custom age buckets using conditional logic</li>
</ul>

<hr>

<h2>❓ Q1: Which Hour Has the Highest Frequency of Crimes?</h2>

<p>
Extracted the hour from <code>TIME OCC</code> and calculated frequency distribution.
</p>

<h3 align="center">🕒 Peak Crime Hour: <span style="color:red;">12:00 PM</span></h3>

<p align="center">
Midday shows the highest recorded crime frequency.
</p>

<hr>

<h2>❓ Q2: Which Area Has the Most Night Crimes? (10PM – 3:59AM)</h2>

<p>
Filtered crimes committed between <strong>22:00 and 03:59</strong> and analyzed area distribution.
</p>

<h3 align="center">🌙 Peak Night Crime Area: <span style="color:red;">Central</span></h3>

<p align="center">
Central recorded <strong>3,162</strong> night-time crimes — the highest among all areas.
</p>

<hr>

<h2>❓ Q3: Crimes by Victim Age Group</h2>

<p>
Created categorized age buckets to better understand demographic distribution.
</p>

<table>
  <tr>
    <th>Age Group</th>
    <th>Number of Crimes</th>
  </tr>
  <tr>
    <td>26-34</td>
    <td>47,470</td>
  </tr>
  <tr>
    <td>35-44</td>
    <td>42,157</td>
  </tr>
  <tr>
    <td>45-54</td>
    <td>28,353</td>
  </tr>
  <tr>
    <td>18-25</td>
    <td>28,291</td>
  </tr>
  <tr>
    <td>55-64</td>
    <td>20,169</td>
  </tr>
  <tr>
    <td>65+</td>
    <td>14,747</td>
  </tr>
  <tr>
    <td>0-17</td>
    <td>4,528</td>
  </tr>
</table>

<p>
<strong>Key Insight:</strong><br>
Individuals aged <strong>26–34</strong> are the most frequently targeted demographic group.
</p>

<hr>

<h2>📊 Key Insights Summary</h2>

<ul>
  <li>🕒 Crime peaks at midday (12 PM)</li>
  <li>🌙 Central area dominates night crime activity</li>
  <li>👥 Age group 26–34 is most affected</li>
  <li>📈 Strong temporal and demographic crime patterns identified</li>
</ul>

<hr>

<h2>🚀 How to Run</h2>

<pre>
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install pandas numpy matplotlib seaborn
python script_name.py
</pre>

<hr>

<h2>📌 Future Enhancements</h2>

<ul>
  <li>📊 Heatmaps for crime density</li>
  <li>🗺️ Geospatial crime mapping</li>
  <li>📈 Time-series trend analysis</li>
  <li>🧠 Predictive crime modeling</li>
  <li>📊 Interactive dashboard (Streamlit / Power BI)</li>
</ul>

<hr>

<h2>👤 Author</h2>

<p>
<strong>Mohamed</strong><br>
Data Analyst | Python Enthusiast
</p>

<p align="center">
  ⭐ If you found this project valuable, consider starring the repository!
</p>
