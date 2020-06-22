# SDP MINI breakout board firmware change to work with HUB Motor setup

We changed our breakout(v6) board firmware to work with ZLAC706 servo motor controllers. Motor controller requests STEP/DIR type of input while the out of the box firware outputs 2 PWM signals for forward and backward control. Aim is to convert the signal types for accurate speed control.

TODO :
 - Testing and calibration of the speed control setup
 - Battery percentage reading through firmware
 - External light/buzzer setup
 - Charging dock setup
