# Report

### GitHub repo
https://github.com/YU-LIN-LIN/ESL_HW4

### General description or introduction of the problem and your solution
	We want to implement Gaussian Blur in riscv-vp platform.  
    Therefore, we need to seperate our design into two parts,  
    software part (testbench) and hardware part (riscv-vp platform).    
	
### Implementation details
	Also use TLM protocal in hardware design by systemC.
    However, we will write our output data to ACC, which is a specific memory address.

### Additional features of your design and models
    The major design is very similar with HW2.  
    There is few additional features through this homework.
	

### Experimental results
	number of instructions (w/o dma) = 86640407.  
    number of instructions (with dma) = 74188552.  

### Discussions and conclusions
	At first, I compile the software part a lot of times but the result is the same as sobel filter.  
    I tried to print the output and look for the reason, everything is still the same though.  
    About two days later, I checked lab8 again, and found that I did not compile the hardware part!  
    This will be impressed upon my mind.  


	
	
