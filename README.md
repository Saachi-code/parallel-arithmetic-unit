# Parallel Arithmetic Unit (PAU) 

**Report:** [ECE242_Final_Report.pdf](./ECE242_Final_Report.pdf)  
**Course:** Digital Systems Testing and Testable Design (ECE 242)  
**Title:** Design, Verification, and Testing of a Parallel Arithmetic Unit  
**Author:** Saachi Jaiswal • **Advisor:** Dr. Reza Raeisi • **Date:** May 2024

## 📖 Summary
Combinational **Parallel Arithmetic Unit (PAU)** that performs **multiplication + addition in parallel** (no MAC-style sequencing). Verified in **ModelSim**, synthesized with **Synopsys Design Compiler** (NanGate 45nm), then **post-synthesis simulation** and **ATPG with Synopsys TetraMAX** for stuck-at fault coverage.  [oai_citation:2‡Saachi_242_Final_Report.pdf](file-service://file-QHCw6qqnLN2T5k5FMBRPVm)

## 📂 Structure
- `verilog/` — RTL & testbench  
  - `Multiplier.v`, `Adder.v`, `p_unit.v`, `tb_p_unit.v`
- `modelsim/` — project/run scripts and wave configs (optional)
- `synthesis_dc/` — DC scripts & reports (`.vg`, `.area`, `.pow`, `.timing`)
- `post_synth_sim/` — gate-level sim files + libraries
- `tetramax_atpg/` — TetraMAX TCL, logs, and generated **test patterns**
- `figures/` — waveform screenshots & schematic views
- `ECE242_Final_Report.pdf` — full write-up

## 🛠️ Tools
ModelSim 10.5b • Synopsys DC / Design Vision • Synopsys TetraMAX • NanGate 45nm OCL.  [oai_citation:3‡Saachi_242_Final_Report.pdf](file-service://file-QHCw6qqnLN2T5k5FMBRPVm)
