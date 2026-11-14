# CA2 — Verilog RTL and Simulation Submission

Submit the Verilog implementation of the design developed in CA1. The implementation must correspond to your group's allotted problem statement and documented architecture.

## What to submit

1. **Verilog RTL**
   - All required synthesizable Verilog modules.
   - Separate FSM/controller and datapath modules, if used.
   - Top-level module integrating the design.
   - Meaningful signal names and comments.

2. **Testbench**
   - Testbench for the complete design.
   - Clock and reset generation, where required.
   - Test cases for normal operation, boundary conditions and important exceptional cases.
   - A self-checking testbench is encouraged where appropriate.

3. **Simulation evidence**
   - Waveforms for important test cases.
   - Screenshots showing key input and output signals.
   - Expected-versus-observed results or a test summary.
   - Brief note on errors found and corrections made, if any.

4. **Implementation notes**
   - FPGA/simulation tool and version used.
   - Top module name and basic simulation instructions.
   - Any changes made to the CA1 design, with reasons.

## Suggested contents inside `CA2`

- `RTL/`
- `Testbench/`
- `Simulation_Waveforms/`
- `Simulation_Screenshots/`
- `Test_Results/`

## CA2 checklist

- [ ] All Verilog source files are uploaded.
- [ ] Top-level module is identified.
- [ ] Testbench is included.
- [ ] Simulation runs and waveforms are provided.
- [ ] Important test cases and observed results are documented.
- [ ] Any changes from CA1 are explained.
