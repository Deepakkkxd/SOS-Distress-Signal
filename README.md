<h1 align="center">🚨 SOS Distress Signaling Project</h1>

<p align="center">
  <strong>Aim:</strong> To blink an LED and sound a buzzer periodically to create an SOS emergency alarm.
</p>

<hr />

<h3>📦 Apparatus Required</h3>
<ul>
  <li><strong>Arduino Uno</strong> (or compatible board)</li>
  <li><strong>LED</strong> (Any color)</li>
  <li><strong>220Ω Resistor</strong></li>
  <li><strong>Buzzer</strong> (Active or Passive)</li>
  <li><strong>Breadboard & Jumper Wires</strong></li>
</ul>

<hr />

<h3>🛠️ Assembly Instructions</h3>
<ol>
  <li><strong>Power:</strong> Connect your Arduino to your computer or power source via USB.</li>
  <li><strong>LED:</strong> Insert the LED into the breadboard.</li>
  <li><strong>Resistor:</strong> Connect the 220Ω resistor to the <strong>Cathode</strong> (the shorter leg).</li>
  <li><strong>Signal:</strong> Connect the <strong>Anode</strong> (longer leg) to <strong>Digital Pin 12</strong> or <strong>13</strong>.</li>
  <li><strong>Ground:</strong> Connect the other end of the resistor to the <strong>GND</strong> pin.</li>
  <li><strong>Upload:</strong> Write your SOS logic in the Arduino IDE and upload!</li>
</ol>

[Image of Arduino SOS signal circuit diagram with LED and buzzer]

<p align="center">
  <img width="450" alt="blink_led_1" src="https://github.com/user-attachments/assets/0cdc4d6d-b1f0-48c6-87d1-61ea0d529d0b" />
  <img width="450" alt="Circuit-design" src="https://github.com/user-attachments/assets/12015880-31af-4d8c-b8b3-5a339f74407a" />
</p>

<hr />

<h3>🔌 Understanding Arduino Pins</h3>
<p><u><strong>1. Digital Pins (Logic 0 or 1)</strong></u><br />
These pins provide digital outputs. They are generally the "unmarked" pins (e.g., 2, 4, 7, 8, 12, 13). They output a binary signal: High (5V) or Low (0V).</p>

[Image of Arduino Uno digital and PWM pins labeled]

<p><u><strong>2. PWM Pins (Simulated Analog)</strong></u><br />
Arduino "fakes" analog signals using <strong>Pulse Width Modulation</strong>. These pins are marked with a tilde (<b>~</b>) symbol (3, 5, 6, 9, 10, 11). They handle 8-bit values ranging from <b>0 to 255</b>.</p>

<p><u><strong>3. ADC Pins (Analog to Digital Converter)</strong></u><br />
Used for processing incoming analog data. The ADC converts these signals into digital values for the Arduino to read
