# Synchronous FIFO Memory

> SystemVerilog Synchronous FIFO Memory  

Implementention in SystemVerilog of __synchronous FIFO memory__.  

## Get Started

The source files  are located at the repository root:

- [Synchronous_FIFO_TB](./Synchronous_FIFO_TB.sv)
- [Synchronous_FIFO](./Synchronous_FIFO.sv)

## Testbench

The testbench comprises three tests for a 32 8-bit word FIFO memory:
1.	Writing to the FIFO memory until it is full
	a.	Verify correctness of written data
	b.	Verify correctness of the FIFO memory full signal
	![ModelSim wave window](./docs/Write_test_wave.GIF)  
	![ModelSim terminal window](./docs/Write_test.GIF)  
2.	Reading from the FIFO memory until it is empty
	a.	Verify correctness of the read data
	b.	Verify correctness of the FIFO memory empty signal
	
3.	Continuous read-write operation with same frequency 


### Possible Applications

Implementation of the synchronous FIFO memory in a complete UART module can be found in the [following repository]((./Synchronous_FIFO.sv))

## Support

I will be happy to answer any questions.  
Approach me here using GitHub Issues or at tom.urkin@gmail.com