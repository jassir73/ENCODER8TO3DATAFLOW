## EXP5:ENCODER 8-3 DATA FLOW MODELLING
# NAME:JASSIR SULTHAN K
# REGISTRATION NO:24901084
**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![Screenshot 2024-11-23 at 22 48 47_36116d31](https://github.com/user-attachments/assets/4406036a-6060-4c56-8f38-e44c87243c04)


Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/user-attachments/assets/dd39cd1c-40db-4fbb-bb07-0e71c4c4c4e0)


The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![Screenshot 2024-11-23 at 22 48 47_2ff87dbc](https://github.com/user-attachments/assets/a45c5ee6-2947-441c-8eb7-ac63ae1c8c0a)


Figure 02  Encoder 8 * 3

**PROGRAM**
![Screenshot 2024-11-23 at 22 48 46_740e20c0](https://github.com/user-attachments/assets/b7e132c9-05e8-48bb-a98f-0f732dca9922)





