Docs and Assorted Part Documentation
====================================

CAD_MicroFC-60035-SMT-C1.pdf
----------------------------
CAD schematic of SensL MicroFC-60035-SMT.  Use for pad diagrams/outlines of SensL detector used here.


UM-MicroC.pdf
-------------
Manual and specifications for Micro_C devices from SensL.  Use for specifications of soldering, as well as design requirements/specifications for detector.


http://www.mantaro.com/resources/impedance-calculator.htm
---------------------------------------------------------
Tool for calculating the impendance of traces/PCB features.  Used to calculate width of traces and impendance match traces for SMA connector/coax.

http://www.analog.com/media/en/technical-documentation/application-notes/an148fa.pdf
------------------------------------------------------------------------------------
Paper/manual detailing how to inhibit oscillations in an opamp, as we're now experiencing.  Some hints: C_parasitic * R_gnd == C_f * R_f in the feedback loop to curtail oscillations.  Reducing R_f and R_gnd can also decrease the likelihood of oscillations.
