NAME : BARKAVI

REFERENCE NAME : 24901000

EXPERIMENT NUMBER : 10 SERIAL IN SERIAL OUT SHIFT REGISTER


**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional table

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

A SISO (Serial-In Serial-Out) shift register is a digital circuit used to store and shift data one bit at a time. It is a fundamental building block in digital electronics, particularly in sequential logic systems. Here is a detailed theory about SISO shift registers:

Definition:
A SISO shift register is a type of shift register where data is input serially (one bit at a time) and output serially, in the same sequence, after a series of clock pulses.


A SISO (Serial-In Serial-Out) shift register is a digital circuit used to store and shift data one bit at a time. It is a fundamental building block in digital electronics, particularly in sequential logic systems. Here is a detailed theory about SISO shift registers:

Definition:
A SISO shift register is a type of shift register where data is input serially (one bit at a time) and output serially, in the same sequence, after a series of clock pulses.

Components:
Flip-Flops:

A series of D-type or JK flip-flops are connected in a chain.
The number of flip-flops determines the length of the register (e.g., 4-bit SISO uses 4 flip-flops).
Clock Signal:

A shared clock drives the flip-flops, synchronizing data movement.
Serial Input (SI):

The data to be stored and shifted enters the first flip-flop through the serial input.
Serial Output (SO):

The shifted data exits the last flip-flop through the serial output.


**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

 write all the steps invloved 

1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram



**PROGRAM**

Program for flipflops and verify its truth table in quartus using Verilog programming.

![Screenshot (126)](https://github.com/user-attachments/assets/c786d878-3573-434b-9908-2486528cc919)


**RTL LOGIC FOR SISO Shift Register**


![Screenshot (124)](https://github.com/user-attachments/assets/ea167c6c-9159-4272-af43-a9b74f636602)

**TIMING DIGRAMS FOR SISO Shift Register**
![Screenshot (125)](https://github.com/user-attachments/assets/fd19fca0-b14c-4354-98c6-35d08ddcb121)


**RESULTS**

The SISO Shift Register using verilog and validating their functionality usingtheir functional tables is verified.
