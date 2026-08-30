# DRAM Verification

RTL design and SystemVerilog/UVM-based verification of a DRAM controller.

## Project Structure

### rtl/
Contains the DRAM RTL design:
- DMA controller
- AXI master
- Descriptor fetch
- FIFO
- Registers
- FSM
- Top-level integration

### tb/
Contains the SystemVerilog/UVM verification environment:
- AXI interface
- UVM agent
- Driver
- Monitor
- Scoreboard
- Register model
- Sequences
- Transactions
- Testbench top

## Verification

The project focuses on functional verification using:
- SystemVerilog
- UVM
- AXI protocol
- Constrained-random stimulus
- Scoreboard-based checking
- Functional coverage
