# LED Power Circuit for RPi

LED Power Circuit for RPi is a power circuit which is a voltage level transfer circuit for the Raspberry Pi. Since the Raspberry Pi specified GPIO voltage is 3.3V and the Max rated source/sink current is 16mA per pin with the total of 50mA from all the pins it is necessary to use a separate circuit to avoid burning the Broadcam IC. 
The circuit could be [directly fixed on top of the Raspberry Pi] as a shield and the output could be taken from the ‘L’ headers located at the edge of the board. 

The circuit is designed only to be used with a set of three parallel LED’s for a cumulative current of 60mA. If the number of LED’s are changing the current limiting resistors (R3,R6,R9) should be changed as required. 

###Documents:
[Schematic diagram]
[Circuit  design]

