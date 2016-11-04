zedboard-axi-dma
================

Demonstration project for the AXI DMA Engine on the ZedBoard

### Description

This project demonstrates the use of the AXI DMA Engine IP for transferring
data between a custom IP block and memory. A tutorial for recreating this project
from the Vivado GUI can be found here:

http://www.fpgadeveloper.com/2014/08/using-the-axi-dma-in-vivado.html

### Requirements

* Vivado 2016.3
* [ZedBoard](http://zedboard.org "ZedBoard")

### Building the SDK workspace

This project uses an example application for the AXI DMA that is located here:

`C:\Xilinx\SDK\<version>\data\embeddedsw\XilinxProcessorIPLib\drivers\axidma_v<ver>\examples\xaxidma_example_sg_poll.c`

The SDK directory of this repo contains a script that can be used to automatically build
an SDK workspace with an application that uses the above mentioned source code. Refer to the
README of the SDK directory for more information.

### License

Feel free to modify the code for your specific application.

### Fork and share

If you port this project to another hardware platform, please send me the
code or push it onto GitHub and send me the link so I can post it on my
website. The more people that benefit, the better.

### About us

This project was developed by [Opsero Inc.](http://opsero.com "Opsero Inc."),
a tight-knit team of FPGA experts delivering FPGA products and design services to start-ups and tech companies. 
Follow our blog, [FPGA Developer](http://www.fpgadeveloper.com "FPGA Developer"), for news, tutorials and
updates on the awesome projects we work on.