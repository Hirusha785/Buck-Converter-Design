<h1>⚡ Buck Converter Design – PSCAD Simulation</h1>

<p>This repository contains the complete design calculations 📑, PSCAD simulation files 💻, and results 📊 for a <b>12 V → 5 V</b> buck converter ⚡ delivering <b>1 A</b> at <b>50 kHz</b> ⏱️.</p>

<hr>

<h2>📋 Project Specifications</h2>
<table>
<tr><th>Parameter</th><th>Symbol</th><th>Value</th></tr>
<tr><td>Input Voltage</td><td>V<sub>in</sub></td><td>12 V</td></tr>
<tr><td>Output Voltage</td><td>V<sub>out</sub></td><td>5 V</td></tr>
<tr><td>Load Current</td><td>I<sub>out</sub></td><td>1 A</td></tr>
<tr><td>Switching Frequency</td><td>f<sub>s</sub></td><td>50 kHz</td></tr>
<tr><td>Inductor</td><td>L</td><td>29.17 mH</td></tr>
<tr><td>Capacitor</td><td>C</td><td>16.66 μF</td></tr>
</table>

<hr>

<h2>🔢 Key Calculations</h2>

<p><b>Duty Cycle</b> 📏<br>
D = V<sub>out</sub> / V<sub>in</sub> = 5 / 12 = <b>0.4167 (41.67%)</b>
</p>

<p><b>Inductor Value</b> 🧲<br>
L = ((V<sub>out</sub> − V<sub>in</sub>) × D) / (f<sub>s</sub> × ΔI) = <b>29.17 mH</b>
</p>

<p><b>Capacitor Value</b> 🔋<br>
C = (D × ΔI) / (f<sub>s</sub> × ΔV) = <b>16.66 μF</b>
</p>

<hr>

<h2>🛠 Files in This Repository</h2>
<ul>
<li><code>Buck Converter Design Calculations.pdf</code> – Calculation sheet</li>
<li><code>Buck Converter Design.pscx</code> – PSCAD simulation file</li>
</ul>

<hr>

<h2>🚀 How to Run</h2>
<ol>
<li>Clone the repository:
<pre><code>git clone https://github.com/Hirusha785/Buck-Converter-Design .git
</code></pre>
</li>
<li>Open <code>buck_converter.pscx</code> in PSCAD.</li>
<li>Run the simulation and observe results in the output plots.</li>
</ol>
<hr>

<h2>📷 Simulation Waveforms</h2>
<p>The following waveforms were obtained from the PSCAD simulation:</p>
<img width="1150" height="576" alt="image" src="https://github.com/user-attachments/assets/d8aae9df-cf3e-44de-b116-1ad4dfa481f0" />
<img width="572" height="287" alt="image" src="https://github.com/user-attachments/assets/4520edc6-1e3c-4b98-b09c-9fa70df81c59" />

<hr>

<h2>📄 License</h2>
<p>This project is open-source under the MIT License.</p>
