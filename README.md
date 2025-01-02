### NAME: B. DHANUSH KUMAR
### REG NO: 24900615
# EXP 6 - SERIAL IN SERIAL OUT SHIFTREGISTER

# AIM:

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

# SOFTWARE REQUIRED:

Quartus prime

# THEORY

# SISO shift Register

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

# Procedure

/* write all the steps invloved */

# PROGRAM
![0fe8505d-994d-4582-9573-9ff85d2534a9](https://github.com/user-attachments/assets/d12403e6-df7a-45f3-95c6-f2c1916accc0)




# RTL LOGIC FOR SISO Shift Register
![3bcc07e2-5482-4a10-aca9-69af08ac3624](https://github.com/user-attachments/assets/a129f629-47d4-40e1-8b8b-ef66dc5c425e)

# TIMING DIGRAMS FOR SISO Shift Register
![3aa8e77c-2008-428a-b5b9-ce42706e34b7](https://github.com/user-attachments/assets/1b94141f-a336-4b2d-acc0-3b71976bb952)

# RESULTS
To implement SISO Shift Register using verilog and validating their functionality using their functional tables.
