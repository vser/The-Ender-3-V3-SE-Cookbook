V1.1 version modification
1.Adjust [safe_z_home] speed to 200
2. Adjust [printer], limit max_accel to 5000, enable max_z_velocity:5, max_z_accel: 100
3. Adjust [extruder], pressure_advance is disabled
4. Adjust [extruder], the nozzle max_temp of ender3S1 PRO is 305, and the max_temp of ender3S1/ender3V2 is 265
5. Adjust [bed_mesh], the speed limit of ender3V2 is 120, and the speed limit of ender3S1 PRO/ender3S1 is 150
6. Add time-lapse photography configuration [include /mnt/UDISK/printer_config/timelapse.cfg]

V1.2 version modification
1. Remove redundant configuration code
2. Modify the [virtual_sdcard] value to path: ~/gcode_files
3. Modify Ender 3V2 [extruder] [heater_bed] value min_temp to 0
4. Added klipper slave computer firmware compilation and installation instructions

V1.3 version modification
1. Urgently fix the problem of CR6SE nozzle heating caused by the [display] field. This field is suitable for dot matrix screens and is useless for sonic screens. Delete this field.
2. Fix the problem that Ender3 V2-CRtouch [stepper_z], enable_pin: !PC3, is not enabled, causing the Z axis not to rise.
3. Modify the model name Ender 3V2-CRtouch to Ender 3V2 ABL

V1.4 version modification
1. Modify Ender3-S1 [safe_z_home] home_xy_position:155,155
2. Modify [stepper_x] homing_speed: 80
3. Modify [stepper_y] homing_speed: 80
4. Modify Ender-3S1/S1 Pro [stepper_y] position_max: 230
5. New model molding size annotation # printer_size: 220x220x270
6. Added [adxl345] spi_speed: 2000000

V1.5 version modification
1. Fixed the issue of out-of-range error during automatic leveling.

V1.6 version modification
1. Remove the Ender3-V2 series material break detection configuration
2. Added Ender3-V2-V4.2.7 motherboard configuration file
3. Added Ender3V2-CRtouch-V4.2.7 motherboard configuration file
4. Modify the configuration file name to a unified style

V1.7 version modification
1. Adapt adaptive leveling and add dual interpolation algorithm
2. Model naming modification specifications

V1.8 version modification
1. Add [verify_heater extruder]
       check_gain_time: 200
       hysteresis: 5
2. Modify the default [extruder] and [heater_bed] PID values

V1.9 version modification
1. Modify [safe_z_home] home_xy_position in Ender3-S1/S1Pro: 145,155
2. Modify [bltouch] x_offset in Ender3-S1/S1Pro: -30.0

V2.0 version modification
1. Modify [printer] max_z_velocity: 10 max_z_accel: 1000 in Ender3-S1/S1 Pro
2. Add Ender3-S1/S1 Pro/V2 [printer] square_corner_velocity: 5.0

V2.1 version modification
1. Modify [stepper_z] position_max in Ender3-S1/S1 Pro: 275
2. Modify [stepper_z] position_max in Ender3-V2: 255

V2.2 version modification
1. Modify the [gcode_macro CANCEL_PRINT] macro definition
2. Modify [stepper_x] position_max in Ender3-V2-CRtouch: 240
3. Update the firmware to add abnormal heating underlying logic

V2.3 version modification
1. Modify Ender3-S1/S1 Pro [stepper_x] position_min: -6 position_endstop: -6
2. Delete Ender3-V2 macro command [delayed_gcode AUTOSTART]

V2.4 version modification
1. Modify Ender3-S1/S1 Pro [stepper_x] position_min: -3 position_endstop: -3

V2.5 version modification
1. Modify Ender3-S1/S1 Pro [stepper_x] position_min: -5 position_endstop: -5
2. Modify the printing and molding range of Ender3-S1/S1 Pro

V2.6 version modification
1.New model Ender3-V2 Neo
2.New model Ender3-s1pro-103
2. Added new macro definition [gcode_macro G29]

V2.7 version modification
1. Modify Ender3-V2-CRtouch-V4.2.7 [stepper_z] to modify touch configuration
