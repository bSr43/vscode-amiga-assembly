**Blitter pointer to source A (high 5 bits)**

This pair of registers contains the 20 bit address of Blitter source (x=A,B,C) or dest. (x=D) DMA data. This pointer must be preloaded with the starting address of the data to be processed by the blitter. After the Blitter is finished, it will contain the last data address (plus increment and modulo).

