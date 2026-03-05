# TalonFXTest

Not affiliated with CTRE or any other companies mentioned here. All trademarks properties of their respective owners

This is simple FRC test code for running a TalonFX motor (currently Falcon 500, but should support Kraken X60 & X44) based on the left joystick position on controller slot 0 in DS.

The motor should run forwards if the joystick is pushed forward, and backwards if the joystick is pushed backwards. The speed is proportional to the joystick position.

The motor is connected over the RIO CAN bus, but should be adaptable for the CANivore so long as that part is changed.

You probably will have to change the CAN ID in the code to reflect the one on your actual motor.
