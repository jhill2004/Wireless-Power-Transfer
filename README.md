# Wireless-Power-Transfer
Create a wireless power transfer transmitter and reciever PCB using Altium Designer.

Model 1: Uses 555 timer to oscillate at resonance frequency of LC circuit to transmit power via magnetic resonance coupling.

Model 2: Uses PLL feedback system to auto oscillate at resonance frequency of LC circuit to transmit power via magnetic resonance coupling. It also uses a 555 to make sure pulses of an appropriate length are inputted into the LC circuit. The resonant waveform is inputted to a comparator to make it a squarewave before being used as the reference waveform of the PLL in order to increase preformance.
Due to the PLL feedback system of model 2, the exact resonance frequency doesn't need to be known for the circuit design. However, an approximate of the resonance frequency can be used to help determine the appropriate length of a pulse. To help approximate the inductance of the trace pcb, this link was used: https://www.66pacific.com/calculators/coil-inductance-calculator.aspx. 

Model 2 Transmitter:
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/f90bf1df-1ab9-466d-902c-652203e0dee1)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/13589d8a-f1c2-4ed6-b540-ab77faa8eba5)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/d0afbd66-637f-405a-85a5-85cb2d7f57b3)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/4379948e-e6ef-4a6f-b74b-3a3d34c19631)

Model 1 Transmitter:
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/03aaa2aa-1d35-42fd-b245-2cef465f3a25)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/60ede105-58de-43f1-9420-f584b2c87a8c)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/894f8b3c-c22e-4502-9ccc-b3b8706d5b41)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/9de58718-266c-46a7-8434-161b05006493)

Model 1 Reciever:
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/562c860d-8926-4cb4-a81e-40e33ff9c40b)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/33dce8e0-1c38-47dc-b1dc-d003eeb9fdcb)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/ab3f77fd-7c7a-4dbc-bda2-e7d4045b8906)
![image](https://github.com/jhill2004/Wireless-Power-Transfer/assets/97457539/3d107507-3aee-47b4-ab86-6d682ffb3ea8)










