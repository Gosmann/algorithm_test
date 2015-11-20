# algorithm_test

Here are all data about the algorithm test to controle de system's angle with the bushless motor.
More information may be found in my project's report: https://drive.google.com/file/d/0B0dmnB3wMg8ebGk5TGh5V25URUE/view?usp=sharing 

brushless_control:
This code may be used in order to calibrate the ESC (electronic speed controller) or simply to control a brushless motor. 
If you want to calibrate yours you'll have to power off the ESC and then upload the code to your Arduino. Once it's done, turn the potentiometer to it's higher value (which would mean maximum speed) and then power on your ESC. You'll hear a "beep" from it, wait 2 seconds and turn the potentiometer to it's lower value, you'll hear two "beeps" this time, and it will mean that your ESC have been calibrated correctly.

PID: This codes control the system with the proportional, integral and derivative algorithm.

PI: This codes control the system with the proportional and integral algorithm.

P: This codes control the system only with the proportional algorithm.

Boolean: This code controls the system using the boolean logic.

