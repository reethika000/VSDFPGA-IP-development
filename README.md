   TASK NAME
   
Development Environment Setup and RISC-V Simulation Flow

   OVERVIEW
   
This task focuses on preparing a reliable FPGA and RISC-V development workflow before starting RTL design or hardware implementation. The objective is to ensure that all required tools, simulators, and repositories work correctly by running a reference RISC-V program and a simulation-based FPGA lab.

TOOLS AND PLATFORM USED

GitHub Codespaces for cloud-based development
Git Bash for local repository management

   TASK EXECUTION DETAILS
   
1. Development Environment Initialization
A clean development environment was launched using GitHub Codespaces. This provided all necessary pre-installed dependencies required for RISC-V compilation and FPGA lab execution. The setup was verified to be stable and ready for further experimentation.
2. RISC-V Toolchain Validation
To confirm the correctness of the toolchain:
A sample RISC-V C program was compiled using the RISC-V GCC compiler
The compiled program was executed using the Spike ISA simulator
The program output was verified to ensure correct execution behavior
This step confirmed that the compiler and simulator were functioning as expected.
3. FPGA Lab Simulation
After validating the RISC-V tools:
The FPGA lab repository was cloned into the same development environment
A basic RISC-V FPGA lab was executed in simulation mode
Firmware was converted into a memory hex format and integrated with the RTL design
The simulation completed successfully, producing the expected output
This step was limited to simulation only; no physical FPGA programming tools were used.
4. Local System Preparation
For better understanding of the tool flow:
The repositories were also cloned on the local machine using Git Bash
The devcontainer configuration was reviewed to analyze required packages and dependencies
FPGA synthesis and board-specific tools were intentionally not installed at this stage

   SUPPORTING MATERIAL
   
Screenshots and execution logs are provided in the repository to demonstrate:
Successful environment setup
Correct RISC-V compilation and execution
Completion of FPGA simulation flow

    KEY TAKEAWAYS
    
This task helped in:
Understanding an industry-oriented FPGA development workflow
Verifying tools before moving to RTL modification or synthesis
Gaining confidence in RISC-V compilation and simulation processes

    CONCLUSION
    
By completing this task, a strong foundation has been established for upcoming FPGA and RTL-based assignments. The validated setup ensures that future development can proceed smoothly without tool-related issues.
