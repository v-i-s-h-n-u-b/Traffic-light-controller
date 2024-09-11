# Traffic-light-controller

A Traffic Light Controller using Verilog HDL, handling state transitions for North-South and
East-West traffic lights with red, yellow, and green signals, including emergency vehicle response and pedestrian crossing.
Implemented different timing parameters for state transitions, including configurable durations for red, yellow, green lights, 
emergency vehicles and pedestrain crossing to simulate realistic traffic light behavior. 

Functionally verified using testbench.

Implemented on the digilent basys 3 artix-7 fpga board

![Screenshot 2024-09-12 033542](https://github.com/user-attachments/assets/a3d86972-3b78-4c3b-b4ed-f46ec5e8391a)
![Screenshot 2024-09-12 033517](https://github.com/user-attachments/assets/8272b2b8-4552-4387-ae5e-105b79c1bd4f)

### Input slide switch mappings

*Slide switch 1 (Pin V17) - clk
*Slide switch 2 (Pin V16) - reset
*Slide switch 3 (Pin W16) - emergency
*Slide switch 4 (Pin W17) - ped_button_NS
*Slide switch 5 (Pin W15) - ped_button_EW

### Output LED mappings

LED 1 (Pin U16) - ped_request_NS
LED 2 (Pin E19) - ped_request_EW
LED 3 (Pin U19) - light_NS[0]
LED 4 (Pin V19) - light_NS[1]
LED 5 (Pin W18) - light_NS[2]
LED 6 (Pin U15) - light_EW[0]
LED 7 (Pin U14) - light_EW[1]
LED 8 (Pin V14) - light_EW[2]   
LED 9 (Pin V13) - shared_ped_light
LED 10 (Pin V3) - state_indicator[0]
LED 11 (Pin W3) - state_indicator[1]
LED 12 (Pin U3) - state_indicator[2]
LED 13 (Pin P3) - state_indicator[3]
LED 14 (Pin N3) - state_indicator[4]
LED 15 (Pin P1) - state_indicator[5]
LED 16 (Pin L1) - state_indicator[6]
             
  
