# SimplePowerSupplies
Four simple power supplies simulated in LTspice. One powers digital circuit with high efficiency, other three power analog circuits, with higher noise requirements.
Technical specialization: 
* 9V DC input, simulated as non ideal source with 100mOhm ESR 
* Measured efficiency, output voltage ripple for 0-100% output load
* Simulated with DC bias effect for capacitors and core saturation effect for coils  

### Analog power supply 1  
* Output voltage - 6V
* Current rating - 500mA
* Structure - LDO, LT3041 used
* Low noise as main goal 

### Digital power supply 
* Output voltage - 1.8V
* Current rating - 2.5A
* Structure - Buck converter, LTC3608 used
* High efficiency as main goal

### Analog power supply 2 
* Output Voltage - -17V
* Current rating - 150mA
* Structure - Inverting Boost converter, LT8580 used
* Low noise as main goal
  
### Analog power supply 3
* Output Voltage - 17V
* Current rating - 150mA
* Structure - Inverting Boost converter, LT1961 used
* Low noise as main goal
