### ENCODER 8TO3 DATAFLOW Modelling

*AIM:* 

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

*SOFTWARE REQUIRED:* Quartus prime

*THEORY*

*Encoder 8 To 3*

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

*Truth Table*

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

*Procedure*
1.Type the program in Quartus software.
2.Compile and run the program.
3.Generate the RTL schematic and save the logic diagram.
4.Create nodes for inputs and outputs to generate the timing diagram.
5.For different input combinations generate the timing diagram

*PROGRAM*

![Screenshot 2024-12-23 104214](https://github.com/user-attachments/assets/d949333e-3184-47c1-8f8c-db01fdf381a3)


/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by: BLESSING S

RegisterNumber: 24002843
*/

*RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling*

![Screenshot 2024-12-23 104230](https://github.com/user-attachments/assets/91fb0692-f350-4155-b3ba-f80d9b3d91ac)


*TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling*

![Screenshot 2024-12-23 104244](https://github.com/user-attachments/assets/58a73a60-8466-4f0a-97a1-e952cd8c7ec2)


*RESULTS*
Thus the Encoder 8 to 3 dataflow circuits are designed and the truth tables is
verified.
