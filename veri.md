# Verilog-Basics

Digital design validation and protocol implementations in synthesizable Verilog

module half\_adder (

&#x20;   input wire a,

&#x20;   input wire b,

&#x20;   output wire sum,

&#x20;   output wire carry

);

&#x20;   assign sum = a ^ b;

&#x20;   assign carry = a \& b;

endmodule



