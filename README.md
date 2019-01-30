# Compiled-Firmware
This repository is for finalized compiled firmware.


# Firmware.HDMBL16.hex contains the following changes:

January 29th 2019

1. Christopher Stahl 7x7 Mesh Bed Leveling aka HDMBL
2. 1/16 Microstepping which equates to 830 steps for a 0.9 degree motor or 415 for those with a 1.8 degree motor
3. increased load and unload length to compensate for added distance bewteen gears and nozzle compared to stock
4. increased unload motor current
5. esteps set to 830 for 0.9 degree motor where these changes are best suited

Best for Prusa MK3 w/ Bondtech extruder w/ 0.9 degree pancake motor. 

Compiled from https://github.com/codiac2600/Prusa-Firmware-HD-MBL

# Firmware.HDMBL32.hex contains the following changes:

January 29th 2019

1. Christopher Stahl 7x7 Mesh Bed Leveling aka HDMBL
2. 1/32 Microstepping stock which equates to 1660 steps for a 0.9 degree motor or 830 for those with a 1.8 degree motor
3. increased load and unload length to compensate for added distance bewteen gears and nozzle compared to stock
4. increased unload motor current
5. esteps set to 830 for 1.8 degree motor where these changes are best suited

Best for Prusa MK3 w/ Bondtech extruder w/ 1.8 degree pancake motor.

Compiled from https://github.com/codiac2600/Prusa-Firmware-HD-MBL

# MK3-BMG16.hex contains the following:

1. Completely stock MK3 firmware 3.5.1
2. 1/16 Microstepping which equates to 830 steps for a 0.9 degree motor or 415 for those with a 1.8 degree motor
3. increased load and unload length to compensate for added distance bewteen gears and nozzle compared to stock
4. increased unload motor current
5. esteps set to 830 for 0.9 degree motor where these changes are best suited

For those who want stock firmware with minor changes for the BMG extruder with a 0.9 degree stepper motor.

# MK3-BMG32.hex contains the following:

1. Completely stock MK3 firmware 3.5.1
2. 1/32 Microstepping which equates to 830 steps for a 0.9 degree motor or 415 for those with a 1.8 degree motor
3. increased load and unload length to compensate for added distance bewteen gears and nozzle compared to stock
4. increased unload motor current
5. esteps set to 830 for 0.9 degree motor where these changes are best suited

For those who want stock firmware with minor changes for the BMG extruder with a 1.8 degree stepper motor.
