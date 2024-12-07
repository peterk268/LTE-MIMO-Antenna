# LTE-MIMO-Antenna
LTE Multiple in Multiple Out Antenna operating at 700MHz simulated in Ansys with optimizations for antenna class project


## Design Method

Altering the length of the antenna arms (L1) tunes the operating frequency of the MIMO antenna. Thus the best bandwidth I found was -6.5dB ignoring the dimension limitations which was a length of 109.5mm which is roughly equal to lambda / 4 which is 429mm / 4 = 107mm.
The issue with this monopole type design is that it won't be resonant, requiring further matching circuits. Although the best bandwidth I achieved while being constrained to the 135mm x 200mm total antenna area was -5dB with a length of 99.5mm.

Next the isolation was influenced by the notch within the ground plane, where the greater the notch the greater the isolation value was with the best value being -15.2dB with a = 50mm and b = 25mm. This is because the ground plane reflects some of the radiation off from one antenna back onto the other antenna causing the coupling. But with that notch in the middle, this gives a pathway for the antennas to radiate away from eachother without the ground plane reflecting the signal back.

<img width="630" alt="image" src="https://github.com/user-attachments/assets/3a5b53d3-2785-4f2c-bb09-9623433d71b8">

## Results
S11 Improved with a & b notch optimization.
![image](https://github.com/user-attachments/assets/310ad53f-659a-462b-99d4-77dac62c005f)

VSWR
![image](https://github.com/user-attachments/assets/7b9526e3-3b7d-40af-b9fc-8c6e34a5a47f)

S21
![image](https://github.com/user-attachments/assets/bcfc7ce2-81c8-43be-975e-fbd05cddd8a0)

Gain 
![image](https://github.com/user-attachments/assets/ea8ec79d-7bd6-49df-8a34-5cd160bcf2fc)
