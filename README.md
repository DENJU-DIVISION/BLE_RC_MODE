# CODE

## How does it work?
Itachi_RC works with an XBOX ONE controller that is paired by BLE (Bluetooth Low Energy). It uses a [BLUEPAD32](https://github.com/ricardoquesada/bluepad32) library. Of all the data, I only use the JOYSTICK data and program the movement speed of the motors.
In theory, you could link any control that is in the [BLUEPAD32](https://github.com/ricardoquesada/bluepad32) list.

***It is necessary to install the [BLUEPAD32](https://github.com/ricardoquesada/bluepad32) library.***

The code named **LOCK_ID_MAC** is used to obtain the *ID MAC* of the controller.
The ID is replaced in the code line of **ITACHI_RC_V1** indicated by a comment.

For the operation of the robot (Xbox One Controller):
- The left joystick is for forward and reverse.
- The right joystick is for turning left and turning right.

