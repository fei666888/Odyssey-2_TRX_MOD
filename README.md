# Odyssey-2_TRX_MOD
Odyssey-2_2017_TRX-LTC2208_version
Modified from Odyssey-2_2017_TRX of N7DDC. Redesigned the schematic and PCB. Because N7DDC uses the PCB designed by lay6, it is not easy to modify and check. I used pads9.5 to redesign it, and keep the PCB size within 10*10, so that it can be realized by JLCPCB cheap to manufacture. The main difference from the N7DDC version:
1. The ADC was replaced by the expensive LTC2165 with the LTC2208.
2. The Ethernet phy is replaced by KSZ9021RL from KSZ9031RN, which is not easy to buy.
3. The PCB size is controlled within 10*10, and the HF-AMP board is connected to the main board through pins, so that different power amplifier boards can be designed more flexibly
4. The power supply part is redesigned, with higher efficiency and lower noise.
