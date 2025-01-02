# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

![Screenshot (169)](https://github.com/user-attachments/assets/537b101a-11b5-4723-b636-25a7981342b4)


 Developed by:MANISHA.M RegisterNumber:24900673
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**

![Screenshot (170)](https://github.com/user-attachments/assets/0caaeec6-90bc-4124-9d29-e2aecba81664)


**TIMING DIGRAMS FOR 4 Bit Ripple Counter**

![Screenshot (171)](https://github.com/user-attachments/assets/81ea6995-510f-4272-9ac7-33739dbc9cb6)


**RESULTS**
BIT RIPPLE COUNTER was studied and verified successfully using quartus software
