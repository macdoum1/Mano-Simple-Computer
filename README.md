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

Memory-Reference
  Direct
    AND
      0xxx
    ADD
      1xxx
    LDA
      2xxx
    STA
      3xxx
    BUN
      4xxx
    BSA
      5xxx
    ISZ
      6xxx
  Indirect
    AND
      8xxx
    ADD
      9xxx
    LDA
      Axxx
    STA
      Bxxx
    BUN
      Cxxx
    BSA
      Dxxx
    ISZ
      Exxx
Register-Reference
  CLA
    7800
  CLE
    7400
  CMA
    7200
  CME
    7100
  CIR
    7080
  CIL
    7040
  INC
    7020
  SPA
    7010
  SNA
    7008
  SZA
    7004
  SZE
    7002
  HLT
    7001
Input-Output
  INP
    F800
  OUT
    F400
  SKI
    F200
  SKO
    F100
  ION
    F080
  IOF
    F040

