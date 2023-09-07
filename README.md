# Basicmodules_Processors-on-Vivado-for-FPGA

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)


## Overview

This repository contains some basic modules of computer architecture along with some small processors using verilog for the implementation on FPGA using Vivado 2018.

## Getting Started

To begin working with the Verilog modules and processors in this repository, follow the steps outlined below.

### Prerequisites

Before you start, ensure you have the following prerequisites in place:

1. **Vivado 2018:** Install Vivado 2018 on your computer. You can download it from the [Xilinx website](https://www.xilinx.com/support/download/index.html/content/xilinx/en/downloadNav/vivado-design-tools/archive.html).

2. **FPGA Hardware:** You should have access to the FPGA hardware you intend to program with the Verilog modules and processors from this repository.


### Installation

**Clone the Repository:**

   ```bash
   git clone https://github.com/msamiullah1080/Basicmodules_Processors-on-Vivado-for-FPGA.git

   ```
### Usage

1. **Open Vivado:**

   Launch Vivado 2018 on your computer.

3. **Open Project:**

   a. Go to "File" > "Project" > "Open existing project..."<br>
   b. Navigate to the project directory you want to open and select **.xpr** file.

4. **Add Verilog Source Files:**

   Once the project is loaded, the source files present in the project will load automatically but you may be required to add sources from other     projects. For this:

      a. In the Vivado project, navigate to "Design Sources." <br>
      b. Right-click on "Design Sources" and select "Add Sources." <br>
      c. Browse to the project directory from which you want to add the source.<br>
      d. Go to ".srcs" > "sources_1" > "new" , here you will find the sources of the project.<br>

6. **Simulate and Synthesize:**

    a. Perform simulation and synthesis of your design using Vivado tools.<br>
    b. Make sure to configure the target FPGA device appropriately during synthesis.<br>
    c. You will ahve to configure constraint file accroding to the need. .xdc file is given in this repository.<br>
    d. Add the corresponding constraint file and uncomment the required ports.<br>

7. **Program the FPGA:**

   Once the design is synthesized successfully, program the FPGA with the generated bitstream.

9. **Test Your Design:**

   Verify the functionality of your Verilog modules and processors on the FPGA hardware.

That's it! You've successfully set up your project in Vivado and implemented Verilog modules on an FPGA. You can now proceed to use and test your design.








