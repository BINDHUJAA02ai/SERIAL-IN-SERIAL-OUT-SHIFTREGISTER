Name:Bindhujaa.S

RegisterNo:24901119

**Experiment06:IMPLEMENTATION OF SERIAL-IN-SERIAL-OUT-SHIFTREGISTER**

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime



**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

1. Initialize the shift register to a known state (e.g., all zeros).

2. Input a bit serially into the shift register.

3. Shift the contents of the register to one position to the right (or left).

4.Output the shifted bit from the last stage of the register.

5.Repeat steps 2-4 for each bit you want to input and shift.





**PROGRAM**

![17362290696322226041717544326238](https://github.com/user-attachments/assets/83a9de12-96fe-4027-ba2f-b19e8cd7ac05)


**RTL LOGIC FOR SISO Shift Register**

![image](https://github.com/user-attachments/assets/062c9c7f-a4a8-477e-a326-588de186fc46)



**TIMING DIGRAMS FOR SISO Shift Register**

![image](https://github.com/user-attachments/assets/de01c3a3-efb6-4d64-a156-169b91a0f0da)


**RESULTS**

The SISO Shift Register using verilog and validating their functionality using their functional tables is verified.
