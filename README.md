# Optimisation Design of IIR Filter using
# Application Specific IC Design

Demonstrated implementation of Optimisation and Unoptimised Variant's Verilog Code Files 

With the evolution of electronic devices, the demand for sophisticated
high performance, low area and low power consumption Application Specific
Processor (ASP) is ever increasing, which aims to process a particular functional
application. This project focuses on design of IIR butterworth filter, which is used
to demonstrate the High Level Synthesis (HLS) design flow providing the
general comprehensive diagnostic pathway to design the same. The proposed
project will proceed using the help of Verilog for coding. The optimised variation
for IIR butterworth filter will be synthesized at RTL. The most optimum result
based on latency time, cycle time and area unit area will be implemented on
Virtex FPGA board.

Application Specific Processors or Circuits are widely used in case of specific
process or application has to be implemented. These circuits are designed for a
specific application. Application Specific Processor (ASP) cores are being
increasingly used to address the demand for high performance, low area and low
power consumption in modern embedded systems. Thus, high constraints lead to
increasing complexity. And increasing complexity leads to variants of solution for
the same problem.
So based upon the above mentioned and Modern-DSE Design Space
Exploration Methods, this project aims to design an optimised ASP i.e design of
IIR Butterworth Filter, in terms of Area,Time required and Number of Resources
used.
The final outcome of this project, the verilog code, aims to be synthesizable in
nature, so the hardware unit designed would be an ASP that is ready to be
synthesized on an ASIC.
The report begins by describing the design problem, objective function,
specifications and operational constraints. Then it provides a preliminary design
approach to the problem by providing possible variants with different
combinations of resources used, with emphasis on data structures.
The report also gives the theoretical background and provides a multiplexing
scheme for different operators derived from the sequencing graph. It then
describes the conversion to block diagram from multiplexing scheme. The report
describes the design of Control Unit and gives the timing specification of control
unit, symbolic representation and gives the development of HDL code from
timing requirements. It is so done after converting the Butterworth filter
equation from frequency domain to time domain.
After which different variants are designed keeping in mind the parameters
(resources, time and area). From which the most Optimized variant is selected
and implemented. Finally it provides the analysis, evaluation and verification of
results and at last, the Conclusion.


ASIC
It stands for application-specific integrated circuit. These are silicon chips
designed for a very specific purpose, created to perform a repeated function very
effectively rather than general purpose chips which can perform an endless
variety of functions, but less efficiently. It is an integrated circuit (IC) chip
customized for a particular use, rather than intended for general purpose use.
Application Specific Processor
ASP has a fixed instruction set for a single purpose. It has the instruction set
necessary to do so. It is never general purpose and for that matter can not
perform some simple tasks if its instruction set does not support it. Its
instruction set is specifically designed to accelerate heavy and most used
functions. Its architecture is designed to implement the assembly instruction set
with minimum hardware cost.
Why Verilog?
Verilog and reason for choosing it over VHDL: Verilog is a Hardware
Description Language; a textual format for describing electronic circuits and
systems. Applied to electronic design, Verilog is intended to be used for
verification through simulation, for timing analysis, for test analysis (testability
analysis and fault grading) and for logic synthesis.
It has support for bidirectional primitives that make it better for ASIC
verification. The preference of VHDL is reducing because it’s verification edge
over Verilog is thoroughly replaced by SystemVerilog. Also, Verilog is already
better in terms of RTL compared to VHDL.
