proteus-ldr-switch
==================
![](Screenshot%202024-02-22%20195004.png)

### Draft
- 5/(IC_in_mA * 10^-3) = total_resistence
- (0.7 / 5) * total_resistence = R2
- currently the R2 is 180ohm, therefore R1 is 820 (for IC_in_mA being 5mA)
- LDR (R1) resistence on super light is around 300ohm (therefore we need dummy resister added in series with R1 to make the ON-OFF criteria more aggressive
### Notes
- Voltage divider make sure base voltage lessor than 0.6-0.7V
- 0.6-0.7 V threshold must work because there must be only 2 state(H/L)
