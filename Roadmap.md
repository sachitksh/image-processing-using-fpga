# image-processing-using-fpga
## Roadmap 
### convert image to binary
To feed the image into verilog, we need to convert it binary (.coe file). We do that using python. The converted image is such that it has as many rows as the total number of pixel and each row having 24 bit (8X3)
### verilog part
chose image processing algorithm
implement Verilog code which can read, process and write images from your system
### fpga part
FPGA implementation which can show the output of the image loaded in block ram on a monitor
make simulation using vivado
