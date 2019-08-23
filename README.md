# UltraCIC_C
Nintendo64 CIC clone written in C

This should run on every MCU which is fast enough to handle the IO operations. You just have to implement the low level gpio functions:
* ReadBit() and
* WriteBit().

Hardware connections
* Data Clock Input (DCLK): CIC Pin 14
* Data Line, Bidir (DIO):  CIC Pin 15
