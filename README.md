<h2>About the Project</h2>
<p>
This is an IoT-based Fire Alarm System developed using Arduino and GSM technology.
The system continuously monitors fire using an IR Flame Sensor and provides instant alerts.
When fire is detected, the system activates a buzzer and automatically sends an alert SMS
and makes a phone call to the registered owner number for immediate notification.
</p>

<h2>System Components</h2>
<ul>
  <li>Arduino UNO</li>
  <li>IR Flame Sensor</li>
  <li>SIM800L GSM Module</li>
  <li>Buzzer</li>
  <li>18650 3.7V Rechargeable Battery</li>
  <li>Breadboard and Jumper Wires</li>
</ul>

<h2>Project Functionality</h2>
<ul>
  <li>Monitors fire using an IR Flame Sensor</li>
  <li>Detects fire in real time</li>
  <li>Activates buzzer when fire is detected</li>
  <li>Sends SMS alert to the owner</li>
  <li>Makes an automatic phone call to the owner</li>
  <li>Ensures quick response and safety</li>
</ul>

<h2>Alert System</h2>
<ul>
  <li>SMS alert sent to registered phone number</li>
  <li>Automatic phone call to the owner</li>
  <li>Local buzzer alarm</li>
</ul>

<h2>Circuit Connections</h2>

<p><strong>IR Flame Sensor</strong></p>
<ul>
  <li>VCC → Arduino 5V</li>
  <li>GND → Arduino GND</li>
  <li>OUT → Arduino Digital Pin D7</li>
</ul>

<p><strong>Buzzer</strong></p>
<ul>
  <li>Positive (+) → Arduino Digital Pin D6</li>
  <li>Negative (–) → Arduino GND</li>
</ul>

<p><strong>SIM800L GSM Module</strong></p>
<ul>
  <li>RX → Arduino TX (D1)</li>
  <li>TX → Arduino RX (D0)</li>
  <li>GND → Common Ground</li>
  <li>VCC → 18650 3.7V Battery Positive</li>
</ul>

<p><strong>Power Supply</strong></p>
<ul>
  <li>18650 Battery (+) → SIM800L VCC</li>
  <li>18650 Battery (–) → Common GND</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li>Embedded C / C++</li>
  <li>Arduino Platform</li>
  <li>GSM Communication (SIM800L)</li>
  <li>Arduino IDE</li>
</ul>

<h2>What Changes Have Been Made</h2>
<ul>
  <li>Added SIM800L GSM module for communication</li>
  <li>Configured owner phone number in Arduino code</li>
  <li>Integrated IR Flame Sensor</li>
  <li>Added buzzer for alert indication</li>
  <li>Implemented SMS and call alert system</li>
</ul>

<h2>Phone Number Configuration</h2>
<ul>
  <li>Open the Arduino <code>.ino</code> file</li>
  <li>Find the phone number variable</li>
  <li>Enter number in international format</li>
  <li>Example: +91XXXXXXXXXX</li>
</ul>

<h2>How to Run the Project</h2>
<ul>
  <li>Download and install Arduino IDE</li>
  <li>Connect Arduino UNO using USB cable</li>
  <li>Make all hardware connections as per circuit</li>
  <li>Insert active SIM card into SIM800L</li>
  <li>Select board: Arduino UNO</li>
  <li>Select correct COM port</li>
  <li>Upload the code to Arduino</li>
</ul>

<h2>Requirements</h2>
<ul>
  <li>Arduino UNO</li>
  <li>SIM800L GSM Module</li>
  <li>IR Flame Sensor</li>
  <li>Buzzer</li>
  <li>18650 Battery</li>
  <li>Breadboard and Jumper Wires</li>
  <li>Arduino IDE</li>
</ul>
