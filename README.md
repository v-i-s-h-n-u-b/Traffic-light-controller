# Traffic-light-controller

A Traffic Light Controller using Verilog HDL, handling state transitions for North-South and
East-West traffic lights with red, yellow, and green signals, including emergency vehicle response and pedestrian crossing.
simulating realistic traffic light behavior. 

### Implemented on the digilent basys 3 artix-7 fpga board (16 user input slide switches, 16 user output LED's)

![Screenshot 2024-09-12 033517](https://github.com/user-attachments/assets/8272b2b8-4552-4387-ae5e-105b79c1bd4f)

### Input Slide Switch mappings

* Slide switch 1 (Pin V17) - clk
* Slide switch 2 (Pin V16) - reset
* Slide switch 3 (Pin W16) - emergency
* Slide switch 4 (Pin W17) - ped_button_NS
* Slide switch 5 (Pin W15) - ped_button_EW

### Output LED mappings

* LED 1 (Pin U16) - ped_request_NS
* LED 2 (Pin E19) - ped_request_EW
* LED 3 (Pin U19) - light_NS[0] - RED
* LED 4 (Pin V19) - light_NS[1] - YELLOW
* LED 5 (Pin W18) - light_NS[2] - GREEN
* LED 6 (Pin U15) - light_EW[0] - RED
* LED 7 (Pin U14) - light_EW[1] - YELLOW
* LED 8 (Pin V14) - light_EW[2] - GREEN   
* LED 9 (Pin V13) - shared_ped_light (ped_light_NS or ped_light_EW)
* LED 10 (Pin V3) - state_indicator[0] - RED_NS_GREEN_EW
* LED 11 (Pin W3) - state_indicator[1] - YELLOW_NS_RED_EW
* LED 12 (Pin U3) - state_indicator[2] - GREEN_NS_RED_EW
* LED 13 (Pin P3) - state_indicator[3] - RED_NS_YELLOW_EW
* LED 14 (Pin N3) - state_indicator[4] - PED_CROSS_NS
* LED 15 (Pin P1) - state_indicator[5] - PED_CROSS_EW
* LED 16 (Pin L1) - state_indicator[6] - EMERGENCY_MODE
             
  
