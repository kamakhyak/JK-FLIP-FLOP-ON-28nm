# JK-FLIP-FLOP-ON-28nm
- This respository presents the Design of JK flip flop.Performance improvement of JK flip flop has been done by using NAND gates. Design is implemented using Synopys Custom Compiler on 28nm CMOS technology.
## Table of Content
- Abstract
- Circuit Details
- Truth Table
- Tools used
- Reference Circuit
- Reference Waveform
- JK Flip Flop
- Schematic
- Waveform
- Delay
- Average Power
- Conclusion
- Author
- Acknowledgement
- Refrence


##Abstract
- The JK flip flop is one of the most used flip flops in digital circuits. The JK flip flop is a universal flip flop having two inputs 'J' and 'K'. In SR flip flop, the 'S' and 'R' are the shortened abbreviated letters for Set and Reset, but J and K are not. The J and K are themselves autonomous letters which are chosen to distinguish the flip flop design from other types.This implementation is done on 28nm technology node using Synopsys tools.The reference waveforms will be verified with actual waveforms obtained from simulation.

## Circuit Details

![jk-flip-flop](https://user-images.githubusercontent.com/86280695/156225877-00c4dc2a-70fd-4f46-a8b8-e37923735be4.png)

## Truth Table

![jk-flip-flop3](https://user-images.githubusercontent.com/86280695/156225966-79f2a1b6-727f-4f6f-ba09-5c40fa82a9fa.png)

## Tools Used
- Synopsys Custom Compiler:The Synopsys Custom Compiler design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.

- Synopsys Primewave:PrimeWave Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.

- Synopsys 28nm PDK:The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

## Refrence Circuit
![JK FLIP FLOP LTSPICE](https://user-images.githubusercontent.com/86280695/156226510-af80c7cf-8970-4875-8a47-e5b6c06c75f3.PNG)

## Refrence Waveform
![LTSPICE GRAPH](https://user-images.githubusercontent.com/86280695/156226573-6e0e87c1-7e3b-45ff-8f88-7840b209fc09.PNG)

## Simulation on Synopsys

### schematic
![jk flip flop](https://user-images.githubusercontent.com/86280695/156226662-a6ee3b60-3614-4a61-a30a-99622adf3ccc.PNG)

### Symbol
![jk flip flop symbol](https://user-images.githubusercontent.com/86280695/156226731-255ffb06-ae13-4dea-a992-571dab9bfb4c.PNG)

### Testbench
![jk flip flop tb](https://user-images.githubusercontent.com/86280695/156226830-a59b034b-6f43-4d90-85ae-7c887fcd4ae2.PNG)
![tb](https://user-images.githubusercontent.com/86280695/156226790-be1a5234-d583-4285-9843-257fd47b0485.PNG)

### Waveform
![graph](https://user-images.githubusercontent.com/86280695/156226892-0a81ae14-e250-476d-a446-c1fe3cace7cb.PNG)

## Conclusion
- The Reference circuit of JK Flip Flop using CMOS mirror logic is successfully implemented using Synopsys tools and simulation waveforms are obtained. The obtained waveforms match with the reference waveforms.

## Autor
- Kamakhya Kaushik, BTech Electronics and Commuincations, ABES Engineering College, Ghaziabad, Uttar Pradesh.

## Acknowledgemet
- Cloud Based Analog IC Design Hackathon
- Synopsys India
- Kunal Ghosh, Co-founder, VSD Corp. Pvt Ltd.
- Chinmay panda, IIT Hyderabad
- Sameer Durgoji, NIT Karnataka
 
 ## References
 - https://www.youtube.com/watch?v=XoBVr_QVBgs&ab_channel=elektrotechniker-aufgabenDotDE
 - https://www.youtube.com/watch?v=j6krFp511HA&t=12s&ab_channel=NesoAcademy




