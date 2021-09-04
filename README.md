# Arduino-HC12-Realy
Arduino script to enable HC-12 radio communication to comand Relay.
This script enable Arduino to communicate with the HC-12 long distance tansceiver (433MHz).
1) Receive chipered commands in the required format
2) if format is ok, proceed to activate relays (support both relay Active HIgh or Active LOW)
3) Transmit an acknowledge command (ACK)

This code is written to communicate with the Hydrosys4 SW instruction format. 
The main view is to provide capability to enable the valves in an irrigation system where the Valves are located far from the controller.
