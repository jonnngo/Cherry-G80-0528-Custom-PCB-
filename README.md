This is a work in progress, I aim to fix/improve upon this first iteration very soon. This project is supposed to be a custom PCB replacement for the Cherry G80-0528 powered by a much more modern microcontroller (STM32F411), QMK firmware, using usb-c.
<img width="2559" height="1392" alt="image" src="https://github.com/user-attachments/assets/bb843dfd-22f3-4a67-bb7f-bee1ac3a52d9" />
<img width="2559" height="1394" alt="image" src="https://github.com/user-attachments/assets/ccd17243-59eb-4f83-af1a-195fd3aea082" />
Some fixes I have planned:
1. The matrix needs to use less microcontroller pins to make room for the LED indicators as well as the crystal oscillator circuit
2. There are two mounting columns that secure the PCB to the keyboard case, which I will need to add holes for
3. Either a daughterboard for the usb-c receptacle, or make sure the usb-c receptacle has proper spacing for a cable to be fixed
