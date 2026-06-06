# -PLC-5---TANK-LEVEL-CONTROL-USING-SCADA

## Aim
To design and implement a tank level monitoring and control system using SCADA software for automatic operation of a water pump based on tank level.

## Objective
Monitor tank water level in real time.
Automatically start and stop the pump.
Display tank level graphically on the SCADA screen.
Generate alarms for high and low water levels.

## Software Required
SCADA Software (infotech.)
PLC Simulator or PLC Hardware
Computer System

## Theory
SCADA (Supervisory Control and Data Acquisition) is used to monitor and control industrial processes. In a tank level control system, the water level is continuously measured and displayed on the SCADA screen. Based on predefined set points, the pump is automatically controlled.
Low Level (20%): Pump starts.
High Level (80%): Pump stops.
Low-Level Alarm: Generated when level falls below 20%.
High-Level Alarm: Generated when level exceeds 80%.
		

## Procedure
Open the SCADA software.
Create a new project.
Configure communication with the PLC or simulator.
Create tags for tank level and pump status.
Design the HMI screen
Draw a tank.
Add a level indicator.
Add a pump symbol.
Add Start and Stop buttons.
Configure animations:
Tank level linked to Tank_Level tag.
Pump color changes when ON.
Run the project.
Observe tank level changes and pump operation

 

## Output



 










## Result
The tank level was successfully monitored and controlled using SCADA software. The pump automatically started at low water levels and stopped at high water levels, while alarms and graphical indications were displayed on the SCADA screen.

