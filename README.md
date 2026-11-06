# Round Robin Arbiter Using Verilog HDL

## Project Overview
This project implements a Round Robin Arbiter using Verilog HDL. The arbiter manages multiple requests for a shared resource using a rotating priority mechanism to provide fair access.

## Key Features
- Round Robin priority scheduling
- Multiple requester arbitration
- Rotating priority mechanism
- Verilog RTL implementation
- Functional simulation using a testbench

## Project Files
- `round_robin_arbiter.v` - RTL design
- `tb_round_robin_arbiter.v` - Simulation testbench

## Tools and Technologies
- Language: Verilog HDL
- Development Platform: EDA Playground
- Simulation: Verilog-compatible simulator

## Working Principle
The arbiter selects a requester based on the current priority. After granting access, priority rotates to give other requesters an opportunity to access the shared resource.

## Verification
A Verilog testbench is used to simulate request and grant behavior and evaluate the arbitration logic.

## Author
Satheesh Kumar M

Integrated M.Tech Computer Science and Engineering
