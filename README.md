
# 4-bit Ring Counter using CMOS 28nm Technology




## Content:
Abstract \
Circuit details\
Circuit diagrams\
Schematic in Synopsys custom compiler\
Testbench\
waveform\
Acknowledgement \
Author\
Reference

## Abstract:
Ring counter is a typical appication of shift register. the only change is the output of last flip flop is connected to the input of first 
.The proposed circuit has been simulated using synopsys custom compiler in 28nm CMOS technology.

## Circuit Details:

The ring counter is a cascaded connection of flip flops, in which the output of last flip flop is connected to input of first flip flop. In ring counter if the output of any stage is 1, then its reminder is 0. The Ring counters transfers the same output throughout the circuit.

That means if the output of the first flip flop is 1, then this is transferred to its next stage i.e. 2nd flip flop. By transferring the output to its next stage, the output of first flip flop becomes 0. And this process continues for all the stages of a ring counter. If we use n flip flops in the ring counter, the ‘1’ is circulated for every n clock cycles

in this design we use master slave flip flop so distortion will we less.


## Circuit diagram :
The circuit diagram of the ring counter is shown below.

![4-bit-Ring-counter (1)](https://user-images.githubusercontent.com/63642795/155894758-e08643e5-c8df-4559-abb3-e03eed4ac561.jpg)

Truth Table 

![Truth-table](https://user-images.githubusercontent.com/63642795/155895019-3f79e7e6-db75-4812-9688-e6cf2488cbc1.jpg)

Master Slave D flip flop 

![images](https://user-images.githubusercontent.com/63642795/155895460-9479d043-8775-44b4-ae99-323f8afccc86.png)

Circuit diagram of Master Slave D flip flop

![393445_1_En_13_Fig1_HTML (1)](https://user-images.githubusercontent.com/63642795/155896301-f684a84c-cb55-48fc-8252-d86f6327e4ee.gif)


## Schematic in Synopsys custom compiler:

master slave D flip flop Schematic 

![schematic_2](https://user-images.githubusercontent.com/63642795/155896471-dd7cdefd-8d28-474b-806c-f852efe22c1a.png)

Symbol 

![1](https://user-images.githubusercontent.com/63642795/155896490-c7e28e09-e5a3-46e0-af04-913de4ca912d.png)


## Testbench:
4-bit ring counter testbench Schematic 

![4_bit_ring_counter_testbench_3](https://user-images.githubusercontent.com/63642795/155896531-860f725c-0cd2-4350-abd8-9aba98533fc0.png)


## waveform:
![4_bit_ring_counter_waveform](https://user-images.githubusercontent.com/63642795/155896559-fc47d177-d82c-424d-a460-4d5b2ba60df7.png)

## Acknowledgement:
[1] Synopsys Company\
[2] IIT Hyderabad\
[3] VLSI System Design (VSD) Corp. Pvt. Ltd. India\
[4] Cloud based Analog IC Design hackathon, IIT Hyderabad\
[5] Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. India\
[6] Chinmaya Panda IIT Hyderabad

## Author
Neel Pambhar , BE in Electronic and Communication Engineering at vishwakarma government engineering college, Ahmedabad 382424
## Reference:
http://www.ijettjournal.org/2016/volume-36/number-4/IJETT-V36P235.pdf

https://www.researchgate.net/publication/338513865_HYBRID_OPTIMIZED_DESIGN_AND_SIMULATION_OF_NEGATIVE_EDGE_TRIGGER_RING_COUNTER_USING_45nm_TECHNOLOGY
