This is a very early work in progress, I aim to fix/improve upon this first iteration very soon. This project is supposed to be a custom PCB replacement for the Cherry G80-0528 powered by a much more modern microcontroller (STM32F411), QMK firmware, using usb-c. Made using KiCad.
<img width="2559" height="1392" alt="image" src="https://github.com/user-attachments/assets/bb843dfd-22f3-4a67-bb7f-bee1ac3a52d9" />
<img width="2559" height="1394" alt="image" src="https://github.com/user-attachments/assets/ccd17243-59eb-4f83-af1a-195fd3aea082" />
Some fixes I have planned:
1. The matrix needs to use less microcontroller pins to make room for the LED indicators as well as the crystal oscillator circuit
2. There are two mounting columns that secure the PCB to the keyboard case, which I will need to add holes for
3. Either a daughterboard for the usb-c receptacle, or make sure the usb-c receptacle has proper spacing for a cable to be fixed


9/2/2026
I have completely redone the schematic and pcb. I squared the matrix making more room for the indicator LEDs, the matrix now takes 22 pins instead of 28. The traces for the columns and rows a little messier now because of this. The "forehead" is much smaller now, so there should be no problems with fixing a cable to the board and fitting in the original case.
1. Still need to add the 2 mounting holes
2. connect the +3.3V pins
3. connect ground pins to the ground planes

<img width="1030" height="807" alt="image" src="https://github.com/user-attachments/assets/e9a1c249-ccbe-4d96-94d1-f4598d74dfe8" />
<img width="1520" height="580" alt="image" src="https://github.com/user-attachments/assets/16a651a0-0285-4202-b29a-68d092e92ef3" />
<img width="1600" height="597" alt="image" src="https://github.com/user-attachments/assets/0bf307d1-2b9b-48e9-9e20-1289310e7c53" />

