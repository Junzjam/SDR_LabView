##Introduction
The codes in HOST file are the antenna selection (AS) function of NBAS Subsystem. While the FPGA intelligence property (IP) in FPGA_IP file is self-designed MUX.  

1. In Host file, the GVI labeled "Selection Main Program" is the main function of NBAS Subsystem. The other GVIs are subfunctions of NBAS Subsystem.
2. In FPGA_IP file, the IP packet "Mul32" is the self-designed MUX to reduce the FPGA Resource and critical path delay. And it will be complied into a bit file "Support.gcomp" for SDR platform calling. 
