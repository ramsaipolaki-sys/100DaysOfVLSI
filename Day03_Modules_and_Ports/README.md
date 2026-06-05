100 Days of VLSI Challenge – Day 3

Today I continued my VLSI learning journey and started understanding the basic structure of Verilog code.

Topic Covered: Verilog Modules & Ports

In Verilog, everything is written inside a module. A module is like a basic building block of digital design.

It communicates with the outside world using ports:

input → receives data into the module output → sends data out of the module inout → bidirectional signal Simple Understanding

I understood it like a real system:

Input → data goes inside the system Output → result comes out of the system Module → the logic working inside Example Verilog Code // Simple AND Gate using Module & Ports

module and_gate ( input a, input b, output y );

assign y = a & b;

endmodule Another Example (Module Structure) // Simple Module Example

module demo_module ( input x, input y, output z );

assign z = x | y; // OR operation

endmodule Why this is important

This is the first step in RTL design. Every Verilog design (adders, FSM, processors) starts with modules and ports.

Next Goal

Start building basic digital circuits using Verilog (AND, OR, NOT, Half Adder).
