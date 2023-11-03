# HW7-Mbed-DSP-Programming

Group : 9  
Member : B09901043 陳昱樺 B09901134 林容丞

Function
---
Here are what this project does:
1. Detect 3D acceleration using accelerator on STM32. 
2. Print the value in the console. 
3. Implement a FIR low pass filter. 
4. Pass the signal through the FIR filter in both STM32 and Python code. 
5. Compare the results between Python and STM32. 

Prerequisites
---
There are two things a user should prepare to run this project:
* STM32 development board
* Python

Usage
---
Here are some steps to run this project properly:
1. Import the project into Mbed Studio. 
2. Run the project on STM32 board with mode 0. 
3. Copy and paste the sensor values to the Python code, and the STM32 filtered results to arm_fir_data.c. 
4. Run the Python code and also copy and paste the result to arm_fir_data.c. 
5. Run the project on STM32 board again but in mode 1. 
6. The successfulness and SNR values are printed in the console. 

License
---
None.

Acknowledgements
---
Here are some resources we refer to to finish this project:
* Course slides: Data Acquisition-.pdf and CMSIS-DSP-Mbed-OS.pdf
