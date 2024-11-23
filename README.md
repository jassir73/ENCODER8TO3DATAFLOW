## EXP5:ENCODER 8-3 DATA FLOW MODELLING
# NAME:JASSIR SULTHAN K
# REGISTRATION NO:24901084

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![Screenshot 2024-11-23 at 22 48 47_9890a163](https://github.com/user-attachments/assets/fe016059-c607-4022-9bbd-84aea714dcf3)


Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**
![Screenshot](https://github.com/user-attachments/assets/f505f134-f2e1-4125-b3d1-44919157f00c)


The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![Screenshot 2024-11-23 at 22 48 47_87ff7bbe](https://github.com/user-attachments/assets/b316cbbd-d9be-416c-bcbd-f77de0359904)

Figure 02  Encoder 8 * 3

**Procedure**

/* write all the steps invloved */

**PROGRAM**


/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: RegisterNumber:24901084
*/

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

**RESULTS**
![Screenshot 2024-11-23 at 22 48 46_229a5d33](https://github.com/user-attachments/assets/273c770a-a00b-428c-9bf8-3eea0b5dea65)




