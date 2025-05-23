# semi-autonomous-car-meam510
 The goal was to create a semi-autonomous car which detects objects emitting IR signals, and autonomously avoid walls / navigate on its own towards destinations we set. 
For XY location tracking we used a Vive "Lighthouse" provided by the class. To construct the design we opted for 2 driving wheels (at the front) and a caster ball at the back to stabilize the car. We are using an ESP32-S2 to control and program the car via WiFi, time of flight (TOF) sensors for object/wall detecting, 1200 RPM motors and drivers, a large rechargeable Li-Po battery and 2 orange wheels. Some of the control we use in our software includes PID control and sensor adjustment. See the Final Project Report below for more information.
[Final Project Report](MEAM%205100%20Final%20Project%20Report.pdf)
<p align="center">
  <img src="brobot-front-view.JPEG"  width="45%"/>
  <img src="brobot-side-view.JPEG"   width="45%"/>
</p>

