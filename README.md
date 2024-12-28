# Single-Cycle-Architecture
This repository implements a **Single Cycle Processor Architecture**, executing one instruction per clock cycle. It supports R-type, I-type, S-type, B-type, JAL, JALR, and U-type instructions. Key components include PC, ALU, and Control Unit, making it ideal for learning CPU basics despite limited efficiency for complex tasks.

To simulate this Single Cycle Processor, follow these steps:

Compile all Verilog files using the vlog command.
Run the testbench in command-line mode using vsim.
View the output waveform using gtkwave.

vlog *.sv  # Compile all Verilog files  
vsim -c tb_processor -voptargs=+acc -do "run -all"  # Run the testbench  
gtkwave processor.vcd  # View the output waveform  
