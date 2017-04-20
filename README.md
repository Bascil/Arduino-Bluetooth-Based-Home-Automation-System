# Arduino-Bluetooth-Based-Home-Automation-System
This system enables you to control your home applicances through bluetooth.

What you need:
-Arduino UNO/Mega or any compatible arduino board
-Android App
-HC-06 Bluetooth Module
-Jumper/Dupont wire
-4 channel 5V relay
-4 Bulbs
-4 Bulb holders
-Connecting wires
-Power cable from 220V AC

CAUTION:This project uses 220V AC power.Proceed at your own risk.Electricity can kill you!!!!!!

Procedure
WIRING
-Power the arduino and upload the arduino code to the arduinoboard
-Connect the Rx pin of HC-06 Bluetooth module to the Tx pin(PIN 1) of arduino
-Connect the Tx pin of HC-06 Bluetooth module to the Rx pin(PIN 0) of arduino
-Connect the VCC of HC-06 Bluetooth module to the 3.3V of arduino
-Connect the GND(ground) pin of HC-06 Bluetooth module to the ground rail of the breadboard
-Connect the GND(ground) pin of arduino uno to the ground rail of the breadboard
-Connect the 5V of Arduino UNO to the power rail of the breadboard
-Connect pins 2,3,4,5 of arduino UNO to IN1,IN2,IN3,1N4 of the relay module
-Connect the VCC pin of relay to the 5V power rail of the breadboard
-Connect the GND(ground) pin of relay to the ground rail of the breadboard
-Strip off the other end of the Power cable from 220V AC to obtain the live and neutral wire(TURN OFF AC POWER WHEN PERFOMING THIS!!!!!!!)
-Make a junction of 4 wires using 4 connecting wires from the LIVE wire and connect to the COM(common) i.e. COM 1,COM2,COM3,COM 4 of the relay module.
-Cut four wires and connect the NO(Normally Open) ie N01,NO2,NO3,NO4 of the relay to the one side of the 4 bulbs(you could use any of the sides of the bulb)
-Make a junction of 4 wires using 4 connecting wires from the NEUTRAL wire and connect to the other side of the 4 bulbs(you could use any of the sides of the bulb)

BLUETOOTH ANDROID APP
-Install the app on an android phone
-Turn on bluetooth on the phone and power the arduino and AC power(the bluetoth LED will turn On and blink severally)
-Pair the H6-06 module with the android phonE.pin is 1234
-Launch the app and type the name of the bluetooth module HC-06 and tap the connect button
-Now the app is ready for use

For enquiries and support towards the project email basilndonga@gmail.com or make comments on GitHub.Thanks
Basil Ndonga




