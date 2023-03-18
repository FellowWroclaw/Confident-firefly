# confident-firefly
Tools for UAV control via cellular 3/4G LTE modem

Introduction:
This project provides a set of tools for controlling unmanned aerial vehicles (UAVs) remotely over a 4G LTE cellular network. The tools rely on the Mavlink communication protocol and other UART-based protocols to interface with the UAV's flight controller.

Requirements:
A UAV with a flight controller that supports the Mavlink communication protocol.
A 4G LTE modem with a SIM card and an active data plan.
A computer or a device with a serial port to connect to the UAV's flight controller.


Installation:
Clone or download the repository to your local machine.
Install the required  packages by running the command 
Configure the config.ini file with the appropriate settings, such as the serial port and baud rate of the UAV's flight controller, and the cellular network's APN and username/password.


Usage:
Connect the computer or device to the UAV's flight controller using a USB or serial cable.
Run the control.py script to establish a connection with the flight controller and the 4G LTE network.
Use the terminal software to send commands to the UAV's flight controller. The commands should follow the Mavlink communication protocol.
The program will receive telemetry data from the UAV and display it on the terminal.

Troubleshooting:
If the program fails to establish a connection with the flight controller, check the serial port and baud rate settings  file.
If the program fails to establish a connection with the cellular network, check the APN and username/password settings  file.
If the program receives incorrect or incomplete data from the flight controller, check the Mavlink communication protocol and the command format.

Limitations:
The program relies on a stable and fast 4G LTE cellular network connection. Poor network conditions may affect the program's performance.
The program only supports the Mavlink communication protocol and other UART-based protocols. Other communication protocols may not be compatible.

Disclaimer:
This program is provided as-is, without any warranties or guarantees of any kind. Use at your own risk.
The user is solely responsible for ensuring that the UAV is operated safely and in compliance with local regulations and laws.


