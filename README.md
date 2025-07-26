# CUSTOM FlightController_F407-H473
The repo contains flight controller target files, PCB Gerber files, and the schematic.


# FC notes 
F407 is based on flying moon FC - H473 is based on matekH473 V3 FC
( f407 uses I2C for all sensors including imu so i can be made at very min cost )

However custom pin can be used unless their usage is not compromised , STM programmer IDE can be a great helpful in case assigning pins.

# FIRMWARE SETUP (Ardupilot)

ARDUPILOT : https://github.com/ArduPilot/ardupilot
Target Files: libraries/AP_HAL_ChibiOS/hwdef/ 

Environment setup : https://ardupilot.org/dev/docs/building-the-code.html

# Target Files 

