# Design and Performance Analysis of Low Power 1-bit Hybrid Full-Adder using 28nm CMOS Technology
# **TABLE OF CONTENT**
1. Abstract
2. Introduction
3. Tool Used
4. Circuit Design
5. Simulation Results 
6. Conclusion
7. Author
8. Acknoledgement
9. Referenecs
## Abstarct -
Adders is very important digital element for any arithmetic operation so it plays a vital role in digital and VLSI systems for ALU.
Now a Day, Technology is moving towards on lowering the scale of transistors for enforcing any other digital system. A novel design of a 
Hybrid Full Adder (FA) using Pass Transistors Logic (PTLs), Transmission Gates (TGs) and Conventional Complementary Metal Oxide Semiconductor (CCMOS) logic is presented.
The hybrid Full Adder cell with 1-bit is implemented in this structure. The proposed method is investigated using 22-nm CMOS hybrid full adder.  
The Average power consumption of 1.1055microwatt with moderately low delay of 7.0415ps was found to be extremely low for 0.8V supply at 28nm technology.
## Introduction 
Adder is a Combinational circuit which perform addition of binary bits. A novel 1-bit hybrid full adder using different types of gates like PTs, TGs, and static CMOS logic was 
introduced. In this type of hybrid full adder was designed by 28nm technology. Modern image and video processing operations, digital signal processing (DSP) chips, microprocessors and many other applications require large scale of arithmetic operations. A 1-bit Full Adder (FA) is considered as the nucleus of binary addition since it is the 
fundamental cell for building wide word-length adders.
### Truth Table of Full Adder

![Full-Adder-truth-table](https://user-images.githubusercontent.com/100580614/156002144-9adc7e2e-4937-4f48-a32a-bb2ab5fef0b0.png)
 
### Block Diagram of Hybrid based Full Adder

![full_adder_block](https://user-images.githubusercontent.com/100580614/156003211-d45e051b-9d80-43ab-ace5-d10b4c238113.PNG)
![Full-Adder-Circuit](https://user-images.githubusercontent.com/100580614/156028686-da58301e-2f79-4a29-bf82-dcbe4f298c4d.png)

## Tool Used 
The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. It delivers industry-leading productivity, performance, and ease-of-use while remaining easy to adopt for users of legacy tools.
Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.
Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.

![WhatsApp Image 2022-02-28 at 20 19 49](https://user-images.githubusercontent.com/100580614/156004024-c0c2ddbd-a31b-4726-b1cf-875f7eafd81a.jpeg)

## Schematic of Circuit 

![IMG_20220228_233130](https://user-images.githubusercontent.com/100580614/156034638-7fab40fc-115b-4c3a-a107-9ae0896332bd.jpg)

 ### Cout Schematic 

![sch_FA_Cout](https://user-images.githubusercontent.com/100580614/156004936-ba2fb129-02d9-4913-b7c1-9a757be9d607.PNG)

### SUM Schematic 

![SCH_FA_SUM](https://user-images.githubusercontent.com/100580614/156005228-2047bc38-bf53-45e1-95d9-ba1d5650fd28.PNG)

### Symbol 

![image](https://user-images.githubusercontent.com/100580614/156029743-a910236b-cf81-4c49-8ba9-e2be7084bb12.png)

### Full Adder Testbench 

![image](https://user-images.githubusercontent.com/100580614/156005665-ff9d4fcb-dcdf-4b3b-a63d-7518053b7b7a.png)

## Simulation Result 

![FA_WF](https://user-images.githubusercontent.com/100580614/156026079-77213b9d-7515-4c77-8586-a87e999ec38a.PNG)

## AUTHOR
SURYAPRATAP RATHORE, M.TECH VLSI 
NATIONAL INSTITUTE OF TECHNOLOGY DELHI, INDIA

## ACKNOWLEDGEMENT 
1. Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. 
2. Synopsys, India
3. VLSI System Design(VSD) Corporation Private Limited India
4. Indian Institute of Technology, Hyderabad (IITH)
5. Cloud Based Analog IC Design Hackathon
6. Sameer Durgoji, NIT Karnataka
7. Chinmay panda, IIT Hyderabad

## REFERENCES

1. Mehedi Hasan, Md. Jobayer Hossein, Mainul Hossain, Hasan U. Zaman, Senior Member,"Design of a Scalable Low-Power 1-bit Hybrid Full Adder for Fast Computation".
2. D. Radhakrishnan, “Low-voltage low-power CMOS full adder,” IEE Proc.-Circuits Devices Syst., vol. 148, no. 1, pp. 19–24, Feb. 2001.


