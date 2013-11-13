Mano-Simple-Computer
====================
Developed by: Michael MacDougall & Peter Swetits

Mano Simple Computer designed in Logicworks 4.6 by Capilano 
Computing Systems.


This was designed in Logicworks 4.6 on Mac OS X and may have 
compatibility issues with Logicworks 5.0 for Windows.

The attached RAM Load Circuit file gives the ability to load a 
RAM module with instructions and operands. This device can then
be copied into the Simple Computer Circuit file and executed.

The instruction set is listed below:

Memory-Reference<br>
  Direct<br>
    AND<br>
      0xxx<br>
    ADD<br>
      1xxx<br>
    LDA<br>
      2xxx<br>
    STA<br>
      3xxx<br>
    BUN<br>
      4xxx<br>
    BSA<br>
      5xxx<br>
    ISZ<br>
      6xxx<br>
  Indirect<br>
    AND<br>
      8xxx<br>
    ADD<br>
      9xxx<br>
    LDA<br>
      Axxx<br>
    STA<br>
      Bxxx<br>
    BUN<br>
      Cxxx<br>
    BSA<br>
      Dxxx<br>
    ISZ<br>
      Exxx<br>
Register-Reference<br>
  CLA<br>
    7800<br>
  CLE<br>
    7400<br>
  CMA<br>
    7200<br>
  CME<br>
    7100<br>
  CIR<br>
    7080<br>
  CIL<br>
    7040<br>
  INC<br>
    7020<br>
  SPA<br>
    7010<br>
  SNA<br>
    7008<br>
  SZA<br>
    7004<br>
  SZE<br>
    7002<br>
  HLT<br>
    7001<br>
Input-Output<br>
  INP<br>
    F800<br>
  OUT<br>
    F400<br>
  SKI<br>
    F200<br>
  SKO<br>
    F100<br>
  ION<br>
    F080<br>
  IOF<br>
    F040<br>

