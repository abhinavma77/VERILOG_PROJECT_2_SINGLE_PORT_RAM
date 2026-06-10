# Day 2 Learning Log

## Concepts Learned

### Memory Declaration
reg [7:0] mem [15:0];

- 16 memory locations
- Each location stores 8 bits

### Write Operation
When we = 1:
mem[addr] <= din;

### Read Operation
When we = 0:
dout <= mem[addr];

### ModelSim
Successfully compiled the RTL without errors.
