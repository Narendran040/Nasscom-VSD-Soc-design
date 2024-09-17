# Digital VLSI SoC Design and planning Training

![Screenshot 2024-09-17 123702](https://github.com/user-attachments/assets/753b2a8c-0d76-46d3-9fb7-1b9f297e367a)

*Two Weeks digital VLSI SoC design and planning workshop with complete RTL2GDSII flow organized by VSD in collaboration with NASSCOM.*

# Open source EDA tools 
https://github.com/kunalg123/vsdflow.git
# OpenLane
https://github.com/The-OpenROAD-Project/OpenLane.git
# Skywater 130 PDK
https://github.com/RTimothyEdwards/open_pdks.git

# Day one
# Theory
<details>
  <summary>
RTL2GDS
  </summary>
 
## RTL to GDS: From Code to Silicon

The RTL to GDS flow is a crucial process in the semiconductor industry, transforming a high-level digital design written at the Register-Transfer Level (RTL) into a layout format (GDSII) that can be used for chip manufacturing. This flow ensures that a design, described through hardware description languages like Verilog or VHDL, is accurately converted into a physical layout that meets performance, area, and power requirements. It involves multiple stages of synthesis, verification, and physical design, culminating in generating the GDSII file, which is essential for fabricating integrated circuits.

![75d437b8-kurssi](https://github.com/user-attachments/assets/d966a5b6-936b-4281-b3db-8989a8af3994)


 # Arduino Uno
 
![Screenshot 2024-05-13 223726](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/b44b49d0-d6d3-4b93-a380-5ee00caedcc5)

![Screenshot 2024-09-06 230404](https://github.com/user-attachments/assets/32ae474d-a61c-4c83-8a01-a1eb250ce51e)


>Package: QFN 48

QFN: Stands for Quad Flat No-Lead. This is a type of surface-mount package where the leads (or pins) are located underneath the package rather than around the sides. This design allows for a smaller footprint and often better thermal performance compared to other package types.

48: This indicates the number of pins or contacts on the package.

![Screenshot 2024-09-06 230708](https://github.com/user-attachments/assets/e86308e6-6923-4d7a-be61-d3d53859aa49)

>CORE,PADS,DIE

Core:

The core refers to the central part of the integrated circuit where the primary functional elements, such as logic gates, processors, or memory cells, are located. It is the heart of the chip, where the actual computations and data processing occur.

Pads:

Pads are small metal contacts on the die's surface where electrical connections are made. They interface with the external package or PCB. Pads include input/output (I/O) pads for connecting signals and power/ground pads for power distribution.

Die:

The die is a small, flat silicon containing the integrated circuit. It is sliced from a larger silicon wafer and includes the core, pads, and other circuitry. After fabrication, the die is usually packaged to protect it and provide connections to the outside world.

![Screenshot 2024-09-06 233032](https://github.com/user-attachments/assets/1d624c52-bc17-45b1-a26d-5ceec1eb7d2f)


>MACROS and FOUNDRY IP'S

 Macros-Macros are pre-designed functional blocks used for various components like processor cores, memory, peripherals, interconnects, and memory controllers. They simplify and speed up the design process, ensuring efficient and reliable system integration.

Foundry IP's-Foundry IPs are pre-designed, verified circuit modules provided by semiconductor foundries. They include standard cells, analog components, and mixed-signal blocks, optimized for specific manufacturing processes. Foundry IPs help streamline IC design by offering proven, process-compatible solutions, improving design efficiency and reliability.


![Screenshot 2024-09-06 234230](https://github.com/user-attachments/assets/deb4fd36-0924-4698-9508-98c58f31391f)


 # Introduction to RISC-V

RISC-V is an open-source instruction set architecture (ISA) known for its flexibility, modularity, and extensibility. Unlike proprietary architectures, RISC-V provides blueprint access, allowing customization for specific applications. Its adoption spans diverse industries, from embedded systems to high-performance computing and AI, due to cost-effective customization, innovation potential, and robust security. RISC-V is hailed as the future of processing, placing customizable technology in developers' hands.

https://users.sussex.ac.uk/~mfb21/compilers/slides/11-handout.pdf

![Screenshot 2024-09-07 112049](https://github.com/user-attachments/assets/688004f6-392d-4587-b59f-d2238fe72ee9)


ISA: ISA is known as "Instruction Set Architecture".It is merely a means of interacting with the computer. Generally speaking, we use coding languages like C, Java, and others to write programs that the system must perform, but machines cannot comprehend these languages. Here's when ISA enters the picture. The written codes will be translated from assembly language to binary, or machine-comprehensible language, using ISA. The RISC V ISA is the most recent ISA to be published, and it serves this purpose.

![Screenshot 2024-09-07 114021](https://github.com/user-attachments/assets/dd436524-4767-4d40-984e-d6264e4985d3)


### 1. **Application Software or Apps:**
   - **Examples:** Mozilla Firefox, Acrobat Reader DC, Oracle VM VirtualBox, Microsoft Office (Word, PowerPoint, Excel).
   - These are end-user programs designed for specific tasks like browsing the web, reading PDFs, or creating documents and presentations. They rely on system software to interact with hardware.

### 2. **System Software:**
   - **Operating System (OS):** Windows, macOS, Linux.
   - The OS handles **I/O operations**, **memory allocation**, and **low-level system functions** like managing hardware resources.
   - The OS also runs software like compilers and assemblers to execute programs written in high-level languages (like C, C++, VB, Java).

### 3. **Compiler:**
   - The compiler translates high-level programming languages (C, C++, VB, Java) into machine-level instructions (Instr1, Instr2, ...). This is typically done by converting the code into an intermediate file, such as a **.exe file** in the case of Windows.

### 4. **Assembler:**
   - The assembler converts these instructions into binary machine code, represented as 1s and 0s (e.g., **1010001110101**).
   - This binary code is what the hardware understands and uses to perform operations.

### 5. **Hardware:**
   - The final destination of the translated code is the physical hardware, which may consist of complex structures like chips (represented in the diagram with Dout1, Dout2, etc.).
   - The binary instructions from the software are directly executed by the hardware to carry out the intended tasks, whether it’s computation, I/O operations, or other low-level functions.


![Screenshot 2024-09-07 114748](https://github.com/user-attachments/assets/4037f33e-c873-438b-8047-ef518c349af7)


![Screenshot 2024-09-07 120414](https://github.com/user-attachments/assets/2b69ac44-7e18-403d-9a14-bee21444ee1f)


![Screenshot 2024-09-07 120723](https://github.com/user-attachments/assets/a00f1784-660e-4380-87f0-9b953aedb67e)


![Screenshot 2024-09-07 122001](https://github.com/user-attachments/assets/749b64ef-4f15-4178-81f6-ba1ed6882955)




 # Open-source digital ASIC design

![asic](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/ad469a48-3080-483d-9aa5-18ad3aa4497c)



1. **ASIC (Application-Specific Integrated Circuit):**
   - The center of the design process, an ASIC is a customized chip designed for a specific application rather than general-purpose computing. For example, ASICs are used in devices like smartphones, data centers, or network equipment.

2. **EDA Tools (Electronic Design Automation):**
   - **EDA Tools** are software used to automate the design, verification, and simulation of ICs. 
   - Examples in this diagram: **QFlow**, **OpenROAD**, and **OpenLANE**. These are all open-source tools for different stages of the ASIC design process, such as physical design, placement, routing, and optimization.
   - These tools help engineers move from a high-level circuit design to the detailed geometric layout that defines how transistors and other components are placed on a chip.

3. **PDK (Process Design Kit) Data:**
   - **PDK Data** provides the essential process-specific information that is necessary to fabricate an ASIC. It includes data about the materials, processes, and rules that govern how the physical structure of the IC is built.
   - This diagram references an **open-source PDK** from **Google** and **SkyWater Technology**, specifically for the **130nm technology node**. The open-source PDK initiative allows designers to experiment and build chips without proprietary licensing barriers.

4. **RTL Designs (Register Transfer Level Designs):**
   - **RTL Designs** describe the behavior and structure of digital circuits in terms of the flow of signals between registers and the logical operations performed on those signals. 
   - Open-source repositories like **librecores.org**, **opencores.org**, and **github.com** host a variety of RTL designs, which designers can use as starting points or reference designs for their projects.




# RTL2GDS flow

![rtl2gds](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/74dcce8e-1fd0-40a2-9535-cb254c1b72f9)



1. **RTL (Register Transfer Level):**
   - The initial design description in terms of data flow and operations (behavior of the circuit), written in hardware description languages (HDL) like Verilog or VHDL.
  

2. **PDK (Process Design Kit):**
   - Contains process-specific rules and data for the chip fabrication technology being used. It guides the design in terms of physical parameters like transistor sizes, layers, and routing rules.

3. **Flow Stages:**

   - **Synthesis (Synth):**
     - The process of converting the high-level RTL code into a **gate-level netlist** (logic gates, flip-flops). This represents the logical structure of the circuit.
       
![Screenshot 2024-09-07 171756](https://github.com/user-attachments/assets/50ba5041-f0b4-46a3-b344-b58c99e65a2f)


![Screenshot 2024-09-07 171808](https://github.com/user-attachments/assets/85af2e86-de19-4dfb-8674-a8e18c8f81d4)



   
   - **Floor Planning + Power Planning (FP + PP):**
     - Determines the layout of major functional blocks on the chip and designs the power distribution network to ensure that all parts of the chip receive power efficiently.

![Screenshot 2024-09-07 171825](https://github.com/user-attachments/assets/9a831096-df1f-4b44-a0b8-daa78e5c3a5e)


![Screenshot 2024-09-07 170935](https://github.com/user-attachments/assets/ff068cbf-e557-44d0-aa7e-9d970ece0e89)

![Screenshot 2024-09-07 171056](https://github.com/user-attachments/assets/39fd98ab-97e9-40a7-8fcb-0c06c43ed917)


   
   - **Placement (Place):**
     - In this stage, the synthesized logic gates are physically placed on the chip according to the floor plan, respecting physical design rules.
    

![Screenshot 2024-09-07 171244](https://github.com/user-attachments/assets/118f0101-a3a1-44e0-81c3-95ed767a2bac)

![Screenshot 2024-09-07 171502](https://github.com/user-attachments/assets/8dc4c6d9-a261-4759-9dd2-6202c3ba3167)


   - **Clock Tree Synthesis (CTS):**
     - The process of designing a **clock tree** that ensures the clock signal reaches all sequential elements (like flip-flops) with minimal skew, ensuring synchronized operations across the chip.
    
 ![Screenshot 2024-09-07 171649](https://github.com/user-attachments/assets/8dc67b53-d0e9-4f70-bd1f-dd6348b53099)


   - **Routing (Route):**
     - Connects the placed cells with actual metal wires according to the design rules provided by the PDK. This step creates the physical connections (nets) between different components on the chip.
    
![Screenshot 2024-09-07 172144](https://github.com/user-attachments/assets/9642481b-880d-4524-96f4-7173be751062)


![Screenshot 2024-09-07 172546](https://github.com/user-attachments/assets/bfcfbb9e-c02c-488d-96b1-081354fd6547)


   - **Sign Off:**
     - This is the final stage where the design is verified against all requirements (timing, power, and design rule checks). Once verified, it is ready for fabrication, generating the final **GDSII** file (Graphical Database System II format).

> Physical verification 

Design Rule Check (DRC): Verifies that the layout follows the foundry's manufacturing rules, such as minimum feature sizes and spacing between components. This ensures the layout is manufacturable.

Layout Versus Schematic (LVS): Compares the layout's extracted netlist with the schematic to ensure that the physical layout matches the intended electrical design, verifying connectivity and device parameters.

>Timing verification

Static Timing Analysis (STA) is a method used to verify the timing of a digital circuit without simulation. It analyzes signal propagation through different paths to ensure the circuit meets its timing requirements.


# OpenLane ASIC flow

![asic flow](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/6121eb04-ac55-498b-b9d1-d44ea569919a)

</details>


### Practical Section-1
<details>
  <summary>
 Basic Linux Commands 
  </summary>

**`cd`** : change directory

**`ls`** : lists the content of the folder

**`pwd`** : shows the present working directory

**`mkdir`** : to make a new directory

**`clear`** : clears the terminal screen




</details>

![Screenshot 2024-09-08 130148](https://github.com/user-attachments/assets/28ab5b40-882b-4862-b0e9-6c8cee0796e9)
<details>
  <summary>
 libs.tech
  </summary>

  ### libs.tech



The `libs.tech` directory contains technology-specific files that are essential for the design, simulation, and verification of ICs using the Skywater 130nm process. The directory  contains folders for various tools such as `magic`, `ngspice`, and others, each tailored to work with the Sky130 PDK. Here’s a detailed breakdown of these tools and their roles:

---

### 1. **`irsim`**:
   - **Purpose**: `irsim` is a switch-level simulator used for digital circuits. It simulates the behavior of logic gates and transistors by treating them as switches.
   - **Files**: Likely contains technology-specific parameters and models needed for simulating digital circuits at the switch level for the Sky130 process.

---

### 2. **`klayout`**:
   - **Purpose**: `klayout` is a GDSII (layout) viewer and editor. It’s used to visualize the physical layout of ICs.
   - **Files**: Contains DRC rules, layer definitions, and possibly script files that allow users to check the layout against the Sky130 technology’s design rules.

---

### 3. **`magic`**:
   - **Purpose**: `magic` is an open-source VLSI layout tool. It’s widely used for physical design and layout editing, particularly in educational and research environments.
   - **Files**: This folder will include:
     - **Technology files**: Describing the layer stack (metal, poly, etc.), design rules, and connectivity information for layout creation.
     - **DRC files**: Rules for design rule checks.
     - **LVS files**: To ensure the layout matches the schematic.

---

### 4. **`netgen`**:
   - **Purpose**: `netgen` is a tool used for LVS (Layout vs. Schematic) verification. It checks whether the physical layout matches the circuit schematic.
   - **Files**: Likely includes the LVS rules that are specific to the Sky130 technology, allowing accurate verification of designs against their schematics.

---

### 5. **`ngspice`**:
   - **Purpose**: `ngspice` is a circuit simulator that simulates analog and mixed-signal circuits.
   - **Files**: Includes SPICE models for transistors and other components, specific to the Sky130 process. These models define the electrical behavior of components at the 130nm node, allowing accurate analog simulations.

---

### 6. **`openlane`**:
   - **Purpose**: `OpenLane` is a fully automated RTL-to-GDSII flow, widely used in digital design. It automates the process from RTL design to final GDSII layout.
   - **Files**: This folder may contain PDK files such as LEF (Library Exchange Format) and Liberty (.lib) files that are necessary for synthesis, place-and-route, and timing analysis within the OpenLane flow.

---

### 7. **`qflow`**:
   - **Purpose**: `Qflow` is another open-source RTL-to-GDSII flow. It’s typically used for simple digital circuit flows.
   - **Files**: Includes technology-specific configuration files and design rules for the Qflow process, allowing it to work with the Sky130 technology.

---

### 8. **`xcircuit`**:
   - **Purpose**: `xcircuit` is a schematic capture tool that can be used for creating circuit diagrams and layouts.
   - **Files**: Contains templates, device symbols, and configuration files that help draw schematics according to the Sky130 process standards.

---

### 9. **`xschem`**:
   - **Purpose**: `xschem` is a schematic capture tool, often used in analog and mixed-signal design.
   - **Files**: This folder likely includes Sky130-specific device libraries, symbols, and configuration files, allowing `xschem` to be used for designing circuits at the schematic level with Skywater’s 130nm PDK.
</details>
     
<details>
  <summary>
 libs.ref
  </summary>



The `libs.ref` directory contains the reference libraries, which are pre-designed, pre-characterized standard cells, memory blocks, and I/O libraries used in the design of integrated circuits using the Skywater 130nm process. These libraries are crucial for digital logic design and are typically used in the synthesis, place-and-route, simulation, and verification stages of the design flow. Here's a breakdown of the contents based on the structure you've provided:

---

### 1. **`sky130_fd_io`**:
   - **Purpose**: Contains the I/O library cells for the Skywater 130nm process.
   - **Files**: This includes I/O cells that handle interfacing between the chip and the external environment. These cells may include voltage level shifting, ESD protection, and signal buffering.
   - **Use**: This is primarily used in the design's input/output pad ring, allowing signals to enter and exit the chip safely.

---

### 2. **`sky130_fd_pr`**:
   - **Purpose**: Likely contains the power-related cells for power distribution and protection within the chip.
   - **Files**: This may include power rings, power pads, ground pads, and other cells that handle power and ground distribution across the chip.
   - **Use**: Essential for ensuring that the design has stable power and ground connections, which is crucial for proper functionality and noise reduction.

---

### 3. **`sky130_fd_sc_hd`** (High Density Standard Cells):
   - **Purpose**: This folder contains high-density standard cells designed for digital logic circuits.
   - **Files**: Includes standard logic gates (AND, OR, NOT), flip-flops, multiplexers, and other combinational and sequential logic cells optimized for high-density layouts.
   - **Use**: Ideal for digital designs where area minimization is critical. These cells are used during synthesis and place-and-route stages to implement logic with minimal area consumption.

---

### 4. **`sky130_fd_sc_hdll`** (High Density Low Leakage):
   - **Purpose**: Contains high-density, low-leakage standard cells.
   - **Files**: These cells are optimized to reduce power leakage, making them suitable for low-power applications while maintaining a compact design.
   - **Use**: Used in power-sensitive designs where reducing static power consumption is a priority, such as in battery-operated devices.

---

### 5. **`sky130_fd_sc_hs`** (High-Speed Standard Cells):
   - **Purpose**: High-speed standard cells designed for performance-critical designs.
   - **Files**: Contains cells optimized for speed at the cost of higher power consumption and possibly larger area.
   - **Use**: Suitable for applications requiring high performance, such as high-frequency processors or high-speed interfaces.

---

### 6. **`sky130_fd_sc_hvl`** (High Voltage Logic Standard Cells):
   - **Purpose**: Contains standard cells designed to operate at higher voltage levels.
   - **Files**: These cells are optimized for designs that require high-voltage operation, which may be necessary for interfacing with certain I/O or mixed-signal circuits.
   - **Use**: Used in designs that need to interface with high-voltage signals or operate in environments where higher voltage tolerance is required.

---

### 7. **`sky130_fd_sc_lp`** (Low Power Standard Cells):
   - **Purpose**: Contains low-power standard cells optimized to reduce dynamic and static power consumption.
   - **Files**: Includes cells that are specifically designed to minimize power usage, suitable for low-power applications.
   - **Use**: Ideal for battery-powered devices and applications where energy efficiency is crucial.

---

### 8. **`sky130_fd_sc_ls`** (Low Speed Standard Cells):
   - **Purpose**: These are low-speed standard cells optimized for low-power and area-efficient designs.
   - **Files**: May include cells that prioritize reduced power and area usage over speed.
   - **Use**: Suitable for applications that don't require high performance but need to minimize area and power consumption.

---

### 9. **`sky130_fd_sc_ms`** (Medium Speed Standard Cells):
   - **Purpose**: Medium-speed standard cells that balance power, performance, and area.
   - **Files**: These cells offer a middle ground between high-speed, high-power cells and low-power, low-speed cells.
   - **Use**: Suitable for general-purpose designs where neither speed nor power is the primary concern, offering a balanced solution.

---

### 10. **`sky130_ml_xx_hd`** (Machine Learning Accelerated High Density):
   - **Purpose**: Likely contains high-density cells optimized for machine learning accelerators or similar high-performance, computation-heavy designs.
   - **Files**: Includes cells optimized for dense computation, potentially featuring specialized structures for matrix multiplication or other ML operations.
   - **Use**: Used in applications requiring efficient computation for machine learning or other high-performance computing tasks.

---

### 11. **`sky130_osu_sc_t18`** (OSU 18-Track Standard Cells):
   - **Purpose**: A specific library developed by OSU (Oklahoma State University) with an 18-track height standard cell library for academic and open-source designs.
   - **Files**: Includes basic logic cells with a unique height of 18 tracks (i.e., the vertical height of the standard cells), used in academic or specific open-source designs.
   - **Use**: Useful for academic purposes, teaching, or specific designs requiring compatibility with the OSU library.



### 12. **`sky130_sram_macros`**:
   - **Purpose**: Contains pre-designed SRAM (Static Random Access Memory) blocks.
   - **Files**: Includes SRAM macros that are pre-characterized and optimized for the Sky130 process. These are highly critical components in many digital designs, especially for data storage.
   - **Use**: Used in designs requiring memory storage, such as processors or ASICs. These pre-designed SRAM blocks save time compared to designing memory from scratch.



  </details>

  ### Design Preparation Steps

  > Invoke Openlane flow and perform synthesis



1. **Change Directory**

  
   ```
   cd Desktop/work/tools/openlane_working_dir/openlane
   ```

2. **Create Docker Alias**

  
   ```
   alias docker='docker run -it -v $(pwd):/openLANE_flow -v $PDK_ROOT:$PDK_ROOT -e 
   PDK_ROOT=$PDK_ROOT -u $(id -u $USER):$(id -g $USER) efabless/openlane:v0.21'
   ```

   

3. **Run the Docker Container**

   Once the alias is set, you can start the OpenLANE flow Docker container by  running
   ```
   docker
   ```
4. **Running the OpenLANE Flow Script in Interactive Mode**
   ```
    ./flow.tcl -interactive
   ```
   The command ``./flow.tcl -interactive runs the flow.tcl `` Tcl script in interactive mode. 
   This starts the OpenLANE design flow, allowing you to interact with the tool in real time and 
   issue additional commands as needed.

5. **Loading the OpenLANE Package in Tcl**
   ```
   % package require openlane
   ```
   The command ``% package requires openlane`` to be used in Tcl (Tool Command Language) to 
   load the OpenLANE package.

6. **Preparing the `picorv32a` Design for Processing** 

   ```
   % prep -design picorv32a
   ```
   The command ``% prep -design picorv32a`` initializes and prepares the ``picorv32a`` design in OpenLANE for further processing.
    
   
![Screenshot 2024-09-08 142336](https://github.com/user-attachments/assets/6a267b30-9ec5-47f0-9eda-d4823b4d0d1c)

7. **Synthesis Process**

   ```
   run_synthesis
   ```

 

![Screenshot 2024-09-08 142408](https://github.com/user-attachments/assets/1138b174-bea0-4569-9f56-ffbd48aa0b04)

 ### Calculate the flop ratio.

![Screenshot 2024-09-08 155653](https://github.com/user-attachments/assets/87f60a6f-6a06-473c-8f93-504ffda6447f)


![Screenshot 2024-09-08 160415](https://github.com/user-attachments/assets/8f7e2189-ccaa-4d7d-94a7-4bad34bd8733)

![Screenshot 2024-09-08 161000](https://github.com/user-attachments/assets/9d4d4964-7c1f-4793-b086-324a9cb871e9)




# Day Two

# Good FloorPlan Vs Bad FloorPlan and Introduction to Library Cells

<details>
  <summary>
  Theory
  </summary>

# Height and Width of core and die

![flll](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/97004977-3bbe-44bd-ad2c-9c8ac3136935)

**Core**: The core is a central area containing the functional logic, such as transistors, logic gates, registers, and memory. It performs the main operations of the chip, excluding peripheral components like I/O pads and power grids. The core's size is optimized for performance, power, and area.


**Die**:The die is the physical semiconductor piece that includes the core and other peripheral components like I/O pads, power grids, and guard rings.

The height and width of the core area will be decided by the netlist of the design. It will be based on the no.of components required to execute the logic and the height and width of the die area will be dependent on the core area height and width.

![Screenshot 2024-09-08 175216](https://github.com/user-attachments/assets/41fa160c-43c2-4f91-930a-abcc6d87c0b8)

FF = Flip Flops/Latches/Registers

A1, 01 = Standard Cells (AND, OR, INVERTER)

The above-shown connections are a netlist with 2 flops and 2 gates.

**netlist**: A "netlist" describes the connectivity of an electronic design.



![Screenshot 2024-09-08 182847](https://github.com/user-attachments/assets/a802c17c-4d1e-4414-bf50-11e0664265ff)
Consider a netlist that has two logic gates and two flipflops each having an area of 1 sq. unit. The netlist contains 4 elements and the minimum total area required for the core area will be 4 sq. units.

![Screenshot 2024-09-08 183905](https://github.com/user-attachments/assets/7d1e8101-9016-49ca-b26f-eb32c0aa4779)

**Utilization Factor**: Utilization Factor is defined as "The ratio of the core area occupied by the netlist to the total core area".For a good FloorPlan, The Utilization Factor should never be '1' because when the Utilization factor becomes '1', there will be no place for adding additional logic if needed and it will be considered as a bad FloorPlan.

**Aspect Ratio**: Aspect Ratio is defined as "The ratio of Height of the core to the width of the core". If the Aspect ratio is '1' , then the core is said to be in a square shape and other than '1' the core will be a rectangle.
 
 
```
 Utilisation Factor =  Area occupied by netlist
                     __________________________
                        Total area of core
```

```
Aspect Ratio =  Height
               ________
                Width
```

![Screenshot 2024-09-08 183905](https://github.com/user-attachments/assets/2e89c686-16b4-435e-971c-4e8c871c10af)

Utilisation Factor = 4 sq.units/4 sq.units=1(1 denotes 100% Utilisation)

Aspect Ratio=(2 units)/(2 units)=1.The core is in a square shape 

![Screenshot 2024-09-08 213139](https://github.com/user-attachments/assets/898a4cbe-99fe-4176-8fce-33973da5fb0e)

Utilisation Factor = (4 sq.units)/(8 sq.units) = 0.5(denotes 50% Utilisation)

Aspect Ratio=(2 units)/(4 units) = 0.5.The core is in a rectangular shape 


</details>



# Practical Section-2
  > Invoke Openlane flow and perform synthesis



1. **Change Directory**

  
   ```
   cd Desktop/work/tools/openlane_working_dir/openlane
   ```

2. **Create Docker Alias**

  
   ```
   alias docker='docker run -it -v $(pwd):/openLANE_flow -v $PDK_ROOT:$PDK_ROOT -e 
   PDK_ROOT=$PDK_ROOT -u $(id -u $USER):$(id -g $USER) efabless/openlane:v0.21'
   ```

   

3. **Run the Docker Container**

   Once the alias is set, you can start the OpenLANE flow Docker container by  running
   ```
   docker
   ```
4. **Running the OpenLANE Flow Script in Interactive Mode**
   ```
    ./flow.tcl -interactive
   ```
   The command ``./flow.tcl -interactive runs the flow.tcl `` Tcl script in interactive mode. 
   This starts the OpenLANE design flow, allowing you to interact with the tool in real time and 
   issue additional commands as needed.

5. **Loading the OpenLANE Package in Tcl**
   ```
   % package require openlane
   ```
   The command ``% package requires openlane`` to be used in Tcl (Tool Command Language) to 
   load the OpenLANE package.

6. **Preparing the `picorv32a` Design for Processing** 

   ```
   % prep -design picorv32a
   ```
   The command ``% prep -design picorv32a`` initializes and prepares the ``picorv32a`` design in OpenLANE for further processing

7. **Synthesis Process**

   ```
   run_synthesis
   ```

8. **To run the picorv32a floorplan in openLANE**

   ```
   run_floorplan
   ```
![Screenshot 2024-09-09 122637](https://github.com/user-attachments/assets/e8fe1639-57da-4d9f-836e-92581c3267ae)

![Screenshot 2024-09-09 122712](https://github.com/user-attachments/assets/be3bfe91-22c9-449d-ba83-7f7f0e0f5a63)
![Screenshot 2024-09-09 130656](https://github.com/user-attachments/assets/a948fdc7-999a-4cfe-8c81-4fd758c9ac3c)

![Screenshot 2024-09-09 130232](https://github.com/user-attachments/assets/62b979e3-4319-45ca-aa7b-83d7eecc7734)



### Die Area Calculation

#### Values:
- **Die width in unit distance**= `660685-0`
- **Die height in unit distance**= `671405-0`

#### Conversion to microns:
Since **1000 unit distance = 1 micron**:

1. **Die width in microns**:
   ```
   660685 / 1000 = 660.685 microns
   ```

2. **Die height in microns**:
   ```
   671405 / 1000 = 671.405 microns
   ```

#### Area of the die in square microns:
     
    
    Area = 660.685 microns * 671.405 microns = 443587.212425 square microns
    
    

 
 . The **area of the die** is approximately **443587.21 square microns**.






# Loading the Floorplan DEF in Magic Tool

### Steps:

1. **Change directory**: Navigate to the folder containing the generated floorplan `.def` file.

```bash
cd Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/09-09_06-53/results/floorplan/
```

2. **Run Magic**: Load the floorplan `.def` file using the Magic tool and the Sky130 technology file.

```bash
magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.floorplan.def &
```

---



![Screenshot 2024-09-09 135635](https://github.com/user-attachments/assets/a1483421-1435-4f9c-ad9d-ed697b049080)

![Screenshot 2024-09-09 141033](https://github.com/user-attachments/assets/bbce151e-be92-4d13-b411-0a71731ee443)

![Screenshot 2024-09-09 142735](https://github.com/user-attachments/assets/596a5056-af9a-4b11-a781-f17c6d808ce9)

![Screenshot 2024-09-09 141225](https://github.com/user-attachments/assets/5d11b1c0-8fc7-4120-a9cd-3bd86f4878d5)

![Screenshot 2024-09-09 142502](https://github.com/user-attachments/assets/2559f451-ed79-4849-82c1-ced0e2ad5b63)

 ![Screenshot 2024-09-09 142647](https://github.com/user-attachments/assets/f7208ba9-c721-44f9-922d-eaae40643a55)
![Screenshot 2024-09-09 142345](https://github.com/user-attachments/assets/4c19a5e6-6e09-42b9-a19d-143ac814eb02)
![Screenshot 2024-09-09 141647](https://github.com/user-attachments/assets/35da3424-88cb-4111-959e-100c540963e7)

![Screenshot 2024-09-09 142427](https://github.com/user-attachments/assets/40df7fa2-8ab0-44af-8a67-b3909f4d07c7)

9. **Placement run on OpenLANE & view in Magic**
```
run_placement
```
![Screenshot 2024-09-09 154021](https://github.com/user-attachments/assets/d74f9dfd-18ed-4490-ace9-a998d7c6c14b)



![Screenshot 2024-09-09 155144](https://github.com/user-attachments/assets/9dab8597-5887-4838-b033-5a493b120a19)



# Loading the Placement DEF in Magic Tool


### Steps:

1. **Change directory**: Navigate to the folder containing the generated placement `.def` file.

```bash
cd Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/09-09_06-53/results/placement/
```

2. **Run Magic**: Load the placement `.def` file in the Magic tool, using the Sky130 technology file.

```bash
magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def &
```



![Screenshot 2024-09-09 155437](https://github.com/user-attachments/assets/70cfee88-957b-443e-9fbb-5d8a1c6f3afe)






# Observing Standard Cell Placement

![Screenshot 2024-09-09 160213](https://github.com/user-attachments/assets/f06c9324-b336-4f21-a9c2-14082a308435)

![Screenshot 2024-09-09 155403](https://github.com/user-attachments/assets/9e6d71a7-f034-4dba-a28c-43cd19808192)

# Standard Cell Design Flow
1. Inputs: PDKs, DRC & LVS rules, SPICE models, libraries, and user-defined specifications.
2. Design steps: Circuit design, Layout design (Art of layout Euler's path and stick diagram), Extraction of parasitics, Characterization (timing, noise, power).
3. Outputs: CDL (circuit description language), LEF, GDSII, extracted SPICE netlist (.cir), timing, noise, and power .lib files

# Timing Parameter Definitions

|Timing defintion|	Value|
|----------------|------|
|slew_low_rise_thr	|20% value|
|slew_high_rise_thr	|80% value|
|slew_low_fall_thr	|20% value|
|slew_high_fall_thr	|80% value|
|in_rise_thr	 |50% value|
|in_fall_thr	 |50% value|
|out_rise_thr	|50% value|
|out_fall_thr	|50% value|

```
rise delay =  time(out_fall_thr) - time(in_rise_thr)

Fall transition time: time(slew_high_fall_thr) - time(slew_low_fall_thr)

Rise transition time: time(slew_high_rise_thr) - time(slew_low_rise_thr)
```



 # Day Three
 <details>
  <summary>
  Theory
  </summary>
 
  # 16 Mask CMOS Fabrication

![16 mask](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/9c0cf9f7-ea5d-4d4f-9d5e-3a5d90593253)


  
> The 16-mask CMOS process consists of the following steps:

1. Selection of substrate: Secting the body/substrate material.
2. Creating active region for transistors: Isolation between active region pockets by SiO2 and Si3N4 deposition followed by photolithography and etching.
3. N-well and P-well formation: Ion implantation by Boron for P-well and by Phosphorous for N-well formation.
4. Formation of gate terminal: NMOS and PMOS gates formed by photolithography techniques.
5. LDD (lightly doped drain) formation: LDD formed to prevent the hot electron effect.
6. Source & drain formation: Screen oxide was added to avoid channeling during implants followed by Arsenic implantation and annealing.
7. Local interconnect formation: Removal of screen oxide by HF etching—deposition of Ti for low-resistant contacts.
8. Higher level metal formation: CMP for planarization followed by TiN and Tungsten deposition. Top SiN layer for chip protection.

 ![16 mp](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/841eec8d-12b8-4c12-bd3f-314421d7642e)

</details>

 # Inverter Standard cell Layout
 The inverter magic file is sourced from vsdstdcelldesign by cloning it within the openlane_working_dir/open lane directory as follows:
 ```
git clone https://github.com/nickson-jose/vsdstdcelldesign
```
![Screenshot 2024-09-10 201222](https://github.com/user-attachments/assets/937290f6-f4af-48b7-84eb-bc14d2231ec2)

**Copying the `sky130A.tech` File to the VSD Standard Cell Design Directory**


```bash
cp sky130A.tech /home/vsdsuser/Desktop/work/tools/openlane_working_dir/openlane/vsdstdcelldesign
```

This command is copying a file named `sky130A.tech` from the current directory into the `/home/vsdsuser/Desktop/work/tools/openlane_working_dir/openlane/vsdstdcelldesign` directory.

The `cp` command is used for copying files in Linux.

![Screenshot 2024-09-10 201939](https://github.com/user-attachments/assets/e81e5f66-0fb0-4188-9ee2-f54c617d32e2)


 **Invoking sky_inv.mag using Magic**

```
magic -T sky130A.tech sky130_inv.mag &
```
![Screenshot 2024-09-10 202313](https://github.com/user-attachments/assets/670cb637-74f9-4a6b-81b6-37f4232dadb4)

![Screenshot 2024-09-10 202413](https://github.com/user-attachments/assets/49ad8b84-3c0f-4c1b-a75f-608c73d1af92)

**NMOS and PMOS Layout in Magic**

![Screenshot 2024-09-10 213508](https://github.com/user-attachments/assets/9439df41-b2c8-4cd3-868c-70062e06654f)

![Screenshot 2024-09-10 213551](https://github.com/user-attachments/assets/01f4b37e-83ca-4873-bd87-1382d8252f56)

![Screenshot 2024-09-10 214307](https://github.com/user-attachments/assets/23baf255-66d5-41a9-af17-b87238370a20)
![Screenshot 2024-09-10 215128](https://github.com/user-attachments/assets/4490df11-d88d-4be2-8c40-7cf2de8b4db5)

![Screenshot 2024-09-10 214208](https://github.com/user-attachments/assets/bafca7f0-c55d-4e70-9018-ab7ab17aafeb)


# Spice extraction



---

### 1. **Check Current Directory**
```bash
pwd
```

---

### 2. **Extract to `.ext` Format**
```bash
extract all
```

---

### 3. **Enable Parasitic Extraction**
```bash
ext2spice cthresh 0 rthresh 0
```

---

### 4. **Convert to SPICE Format**
```bash
ext2spice
```

---
![Screenshot 2024-09-11 221959](https://github.com/user-attachments/assets/4a167ef3-a416-4eb4-a033-0d252c5d6190)

![Screenshot 2024-09-11 222022](https://github.com/user-attachments/assets/f29af110-bbc4-4d30-af15-ec6ba4185cd9)


![Screenshot 2024-09-11 222126](https://github.com/user-attachments/assets/8778f590-2112-479d-8bf3-bfbe79f55177)

**Edited spice file ready for ngspice simulation**
![Screenshot 2024-09-12 164226](https://github.com/user-attachments/assets/e125230f-ad00-43ae-bdd8-a31838a110f4)
![Screenshot 2024-09-12 164156](https://github.com/user-attachments/assets/5b084dc6-342a-4e7f-8c5d-e60a061b92f2)

![Screenshot 2024-09-12 164323](https://github.com/user-attachments/assets/03dc0d08-14e6-4c67-a578-d7ebcd50e1cf)

![Screenshot 2024-09-12 213139](https://github.com/user-attachments/assets/2108b7ed-f532-416b-bfd3-8df176b63a3c)

![Screenshot 2024-09-12 213156](https://github.com/user-attachments/assets/b0f0ce9f-b416-4550-8dd9-cf74f60a8ee0)

![Screenshot 2024-09-12 213346](https://github.com/user-attachments/assets/6566617b-801d-4f9b-a61c-b74dbb1352c1)
![Screenshot 2024-09-12 213404](https://github.com/user-attachments/assets/8bce9b66-44de-4d9f-b77a-fd64cbdff91b)


### Rise Transition Time Calculation

We calculate the rise transition time as follows:

```
Rise transition time = 2.20029 -2.17992= 0.02037 ns
```

Which can be converted to picoseconds (ps):

```
 0.02037 ns = 20.37 ps
```

Thus, the rise transition time is **20.37 ps**.

![Screenshot 2024-09-12 213911](https://github.com/user-attachments/assets/0024bc32-9acb-4ff5-bae5-03a4bf2c9234)

![Screenshot 2024-09-12 213924](https://github.com/user-attachments/assets/5f2d25c9-2f68-4325-b90a-a245b7f6d8bc)

![Screenshot 2024-09-12 214220](https://github.com/user-attachments/assets/c3dfe9d8-e74f-40ea-b7ce-d3c299bf5c6b)

![Screenshot 2024-09-12 214234](https://github.com/user-attachments/assets/862ef825-b012-4ca3-9a03-f25f8a75a32c)



### Fall Transition Time Calculation

We calculate the rise transition time as follows:

```
Fall transition time = 4.06673-4.04015 = 0.02658 ns
```

Which can be converted to picoseconds (ps):

```
0.02658 ns = 26.58 ps
```

Thus, the Fall transition time is **29.99 ps**.



![Screenshot 2024-09-12 221231](https://github.com/user-attachments/assets/7dc4135a-8775-46b4-890e-f2d0b9b427e4)

![Screenshot 2024-09-12 221245](https://github.com/user-attachments/assets/48bc3fb2-0684-43bd-ae0d-75330e3c70e7)
**Rise Cell Delay**
```
Rise Cell Delay= 2.1808-2.18092=-0.00012 ns
```
Which can be converted to picoseconds (ps):
```
-0.00012 ns=-00.12 ps
```
Thus, the Rise cell delay is **-00.12 ps**

![Screenshot 2024-09-12 221423](https://github.com/user-attachments/assets/8c81ccde-6a80-4ff0-9026-95a8b1569cf2)


![Screenshot 2024-09-12 221436](https://github.com/user-attachments/assets/9ef7d42a-f530-4f0c-aee7-c197181fc4c6)
**Fall Cell Delay**
```
Fall Cell Delay= 4.05343-4.05354=-0.00011 ns
```
Which can be converted to picoseconds (ps):
```
-0.00011 ns =-00.11 ps
```
Thus, the Fall cell delay is **-00.11 ps**

# Lab introduction to Magic tool options and DRC rules

*Google_Skywaters Design Rules*: https://skywater-pdk.readthedocs.io/en/main/rules/periphery.html

```bash
# Step 1: Change to the home directory
cd

# Step 2: Download the lab files
wget http://opencircuitdesign.com/open_pdks/archive/drc_tests.tgz

# Step 3: Extract the compressed lab files
tar xfz drc_tests.tgz

# Step 4: Change directory into the lab folder
cd drc_tests

# Step 5: List all files and directories with detailed information
ls -al

# Step 6: View the .magicrc file using gvim
gvim .magicrc

# Step 7: Open Magic tool with better graphics (using XR display)
magic -d XR &
```
![Screenshot 2024-09-13 141647](https://github.com/user-attachments/assets/51fbbe72-f7f2-4bd9-9bc0-aa5b9be59e6c)

![Screenshot 2024-09-13 141726](https://github.com/user-attachments/assets/661bfa84-40ff-4424-a568-e7a4071876ae)


![Screenshot 2024-09-13 141713](https://github.com/user-attachments/assets/a6098ea0-14cf-4397-bfc2-9154602c0c14)

![Screenshot 2024-09-13 141746](https://github.com/user-attachments/assets/99a984ce-39c6-4228-a4e3-f23dce42654e)

![Screenshot 2024-09-13 141800](https://github.com/user-attachments/assets/40b8d89d-da5e-48fe-b9c3-3364dc3dd7e8)



![Screenshot 2024-09-13 141813](https://github.com/user-attachments/assets/d65158ca-c6ca-44f4-bc84-74c36057b8a8)



![Screenshot 2024-09-13 141904](https://github.com/user-attachments/assets/7aed06eb-a581-49ba-8f58-0b9d04f77d8c)

![Screenshot 2024-09-13 142017](https://github.com/user-attachments/assets/ca470c6b-c5ee-48fe-9516-affd9a714a81)

*These rules can be found in the Google-SkyWater documentation.*
![Screenshot 2024-09-13 142240](https://github.com/user-attachments/assets/5b6ff33d-36d6-4a52-b8dc-df8ad9e85919)
 
 Select any layout area and check the **drc why** it is in tckon.

![Screenshot 2024-09-13 152338](https://github.com/user-attachments/assets/08418a47-4dc9-4016-a881-6ed5ab689cbe)
Next, select a blank area and hover the mouse pointer over the metal3 contact icon. Press the p button and type 'pek' in the tkcon. Then execute the command **cif see VIA2** in the tkcon tab.


![Screenshot 2024-09-13 161146](https://github.com/user-attachments/assets/4e84f6be-5d75-4bad-ac32-c843a338546c)

**Lab exercise to fix poly.9 error in Sky130 tech-file**

Now, we will open the poly. mag file in the magic tool with the help of the command **load poly. mag** in the tkcon terminal.
![Screenshot 2024-09-13 161631](https://github.com/user-attachments/assets/5f8c1e76-4f3f-4e76-a2d2-88a4764c79dc)
![Screenshot 2024-09-13 161616](https://github.com/user-attachments/assets/648c1870-b9e5-401c-a4aa-f0640760c112)


![Screenshot 2024-09-13 161859](https://github.com/user-attachments/assets/9430bb12-c9f9-4096-b10b-3f59671a3812)

![Screenshot 2024-09-13 161919](https://github.com/user-attachments/assets/aec61f2b-ed0f-4263-8c2b-7ad2361e841d)


![Screenshot 2024-09-13 162239](https://github.com/user-attachments/assets/0b5302e6-b728-437a-ad74-cccc29cd6890)
![Screenshot 2024-09-14 135136](https://github.com/user-attachments/assets/2515f4da-c0e3-4856-88f1-fad6273fdc7d)

![Screenshot 2024-09-14 141732](https://github.com/user-attachments/assets/3ba33e5c-dacb-4bf3-999d-926186e53f7d)

To find the error, open the `sky130A.tech` file located in the `drc_tests` directory using a Linux text editor.
![Screenshot 2024-09-14 134957](https://github.com/user-attachments/assets/ae9a8898-d30b-41af-8dc2-34e49ce45f80)

Search for 'poly.9' in the `sky130A.tech` file, found in both the POLY and uhrpoly sections, and update the rules where they are incorrectly set.
![Screenshot 2024-09-13 172122](https://github.com/user-attachments/assets/a6ffd620-6ebc-431e-acff-ae4f1b404045)

![Screenshot 2024-09-13 172254](https://github.com/user-attachments/assets/120f6bec-2884-404e-b42d-951aee6d8679)

 Execute the command tech `load sky130A.tech` in the tkcon terminal. Then, run the drc check as shown below.

 ![Screenshot 2024-09-13 172524](https://github.com/user-attachments/assets/67bd8437-e6fb-4328-93d1-954dd3b4f122)

To check for errors, copy the poly.9 model from the `poly.mag` file in the Magic window.
![Screenshot 2024-09-14 120547](https://github.com/user-attachments/assets/d4dada4d-019b-4783-ac33-98faa462d018)

To find the description of a DRC error, select the error area in the Magic window and run the command `drc why` in the tkcon terminal.
![ScreenshoNow we will make the following changes to the `sky130A.tech` file:t 2024-09-14 120613](https://github.com/user-attachments/assets/8dd509f3-d9de-41c4-90cb-d69c0776f41d)

Lab challenge exercise: describe the DRC error as a geometrical construct.
Now we will make the following changes to the `sky130A.tech` file:

![Screenshot 2024-09-14 123117](https://github.com/user-attachments/assets/37be9eaa-701a-45d2-b7b5-c40462e06629)

![Screenshot 2024-09-14 122753](https://github.com/user-attachments/assets/96f7bb3f-7b9d-4040-9970-ce385f5ddcb0)

To find the `nwell.6` model error, open the `nwell.mag` file in the Magic tool. In the figure, the deep nwell is shown with yellow stripes, and the nwell is shown with a dotted green pattern.

![Screenshot 2024-09-14 144826](https://github.com/user-attachments/assets/16bfe3c7-320e-4bb8-876a-ce1e4949c66b)

The error can be seen on the site.
![Screenshot 2024-09-14 145719](https://github.com/user-attachments/assets/78ef8da0-b2c1-459f-a616-88934de08b72)


2. Execute the command `drc style`.
3. Run the command `drc(full)`.
4. Perform the `drc check` command.

![Screenshot 2024-09-14 124723](https://github.com/user-attachments/assets/befa403a-961e-480f-917f-16eb240123b9)

 # Day Four
 

 
  A requirement for ports as specified in tracks.info is that they should be at the intersection of horizontal and vertical tracks. The CMOS Inverter ports A and Y are on the li1 layer. It must be ensured that they're on the intersection of horizontal and vertical tracks. We access the tracks.info 
  


1. **Change Directory:**
   ```bash
   cd Desktop/work/tools/openlane_working_dir/openlane/vsdstdcelldesign
   ```
 

2. **Open Custom Inverter Layout in Magic:**
   ```bash
   magic -T sky130A.tech sky130_inv.mag &
   ```
   


![Screenshot 2024-09-14 152906](https://github.com/user-attachments/assets/7d739ad4-8755-48f6-815a-f68274db45a9)

  
  


  To ensure that ports lie on the intersection point, the grid spacing in Magic (tkcon) must be changed to the li1 X and li1 Y values. Convergence of grid and tracks can be achieved using the following command:
  
 To set the grid values in Magic, you can use the `grid` command. :

1. **Get Syntax for Grid Command:**
   ```bash
   help grid
   ```
   This command will show you the syntax and options available for the `grid` command in Magic.

2. **Set Grid Values:**
   ```bash
   grid 0.46um 0.34um 0.23um 0.17um
   ```
   This command sets the grid values as follows:
   - **0.46um**: X-grid spacing (main grid)
   - **0.34um**: Y-grid spacing (main grid)
   - **0.23um**: X-grid spacing (minor grid)
   - **0.17um**: Y-grid spacing (minor grid)

![Screenshot 2024-09-14 154445](https://github.com/user-attachments/assets/31dabf33-1d8a-4d88-b0a9-d3f0af97fea5)

**Condition 1 verified**

![Screenshot 2024-09-14 154823](https://github.com/user-attachments/assets/306b933a-6991-4e1c-8da8-02553f6b2861)

**Condition 2 verified**

**Horizontal track pitch = 0.46 µm**
![Screenshot 2024-09-14 182718](https://github.com/user-attachments/assets/31c28f8f-66b7-4e54-be10-75252c765d32)

**Width of standard cell = 1.38 µm = 0.46 µm × 3**

**Condition 3 verified**

**Vertical track pitch = 0.34 µm**

![Screenshot 2024-09-14 183006](https://github.com/user-attachments/assets/9f2c2ac8-d47f-4aea-bdf1-9a5698d58831)

**Height of standard cell = 2.72 µm = 0.34 µm × 8**

To save and open a layout with custom names in Magic, you would use the following commands:

### Saving the Layout
To save the current layout with a custom name, use the `save` command in the Tkcon window:

```tcl
save sky130_vsdinv.mag
```

This command will save the currently open layout as `sky130_vsdinv.mag`.

### Opening the Layout
To open the newly saved layout in Magic, use the `magic` command in your terminal:

```bash
magic -T sky130A.tech sky130_vsdinv.mag &
```

Here's a brief explanation:
- `-T sky130A.tech`: Specifies the technology file to use.
- `sky130_vsdinv.mag`: The name of the layout file you want to open.
- `&`: Runs the command in the background, allowing you to continue using the terminal.


*Newly saved layout*
![Screenshot 2024-09-14 185409](https://github.com/user-attachments/assets/e5335a83-f433-404e-a1f6-78e717a09b49)


 **LEF extraction can be carried out in tkcon:**
 
 Command for tkcon window to write lef

**lef command**
```
lef write
```
![Screenshot 2024-09-14 185801](https://github.com/user-attachments/assets/db42c4e6-cfa7-4527-a5a6-775bf1ce22ec)

 *Newly created lef file*
 
![Screenshot 2024-09-14 191303](https://github.com/user-attachments/assets/29bbb0da-0aa2-457b-8dca-62cb0b1afa3f)

**Copying Custom LEF and Required LIB Files to `picorv32a` Design's src Directory**

### Copying the LEF File:
```bash
# Copy the custom LEF file to the src directory of picorv32a
cp sky130_vsdinv.lef ~/Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/src/
```

### Verifying LEF File Copy:
```bash
# List files in the src directory to confirm the LEF file is copied
ls ~/Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/src/
```

### Copying the Required LIB Files:
```bash
# Copy the required LIB files to the src directory of picorv32a
cp libs/sky130_fd_sc_hd__* ~/Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/src/
```

### Verifying LIB Files Copy:
```bash
# List files in the src directory to confirm the LIB files are copied
ls ~/Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/src/
```
![Screenshot 2024-09-14 193544](https://github.com/user-attachments/assets/34ad96e3-5ce2-463f-bdc9-3b15e06aeb4a)

 **Edit 'config.tcl' to change lib file and add the new extra lef into the openlane flow.**

### 1. **Setting the LIB Files:**
```tcl
# Set the path for the synthesized library (LIB_SYNTH)
set ::env(LIB_SYNTH) "$::env(OPENLANE_ROOT)/designs/picorv32a/src/sky130_fd_sc_hd__typical.lib"

# Set the path for the fastest library (LIB_FASTEST)
set ::env(LIB_FASTEST) "$::env(OPENLANE_ROOT)/designs/picorv32a/src/sky130_fd_sc_hd__fast.lib"

# Set the path for the slowest library (LIB_SLOWEST)
set ::env(LIB_SLOWEST) "$::env(OPENLANE_ROOT)/designs/picorv32a/src/sky130_fd_sc_hd__slow.lib"

# Set the path for the typical library (LIB_TYPICAL)
set ::env(LIB_TYPICAL) "$::env(OPENLANE_ROOT)/designs/picorv32a/src/sky130_fd_sc_hd__typical.lib"
```

### 2. **Adding the Custom LEF File:**
```tcl
# Add extra LEF files, including the custom LEF
set ::env(EXTRA_LEFS) [glob $::env(OPENLANE_ROOT)/designs/$::env(DESIGN_NAME)/src/*.lef]
```

### Final Steps:
1. Save the `config.tcl` file with these changes.
2. When you run the OpenLane flow, it will automatically use the modified library paths and include your custom cell's LEF file.



![Screenshot 2024-09-14 201023](https://github.com/user-attachments/assets/1e134c02-2e71-411e-bd98-f8846c5f7fe8)





### Invoking OpenLANE Flow, Including New LEF, and Running Synthesis for `picorv32a`

```bash
# Change directory to openlane flow directory
cd Desktop/work/tools/openlane_working_dir/openlane

# Alias for Docker OpenLANE invocation
# alias docker='docker run -it -v $(pwd):/openLANE_flow -v $PDK_ROOT:$PDK_ROOT -e PDK_ROOT=$PDK_ROOT -u $(id -u $USER):$(id -g $USER) efabless/openlane:v0.21'

# Invoke Docker (using the alias)
docker

# Enter the OpenLANE flow in interactive mode
./flow.tcl -interactive

# Load OpenLANE package
package require openlane 0.9

# Prepare the design files for 'picorv32a'
prep -design picorv32a

# Additional commands to include newly added LEF to OpenLANE flow
set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
add_lefs -src $lefs

# Run synthesis for the design
run_synthesis
```

![Screenshot 2024-09-14 201252](https://github.com/user-attachments/assets/27dff388-210c-4223-a6ad-a0c5b0adce2a)

![Screenshot 2024-09-14 201411](https://github.com/user-attachments/assets/0e28690f-44ba-41aa-8c44-c1d489c0df5a)

**Reduce the newly introduced violations with the introduction of custom inverter cell by modifying design parameters.**

Note the current design values generated before modifying parameters to improve timing.
![Screenshot 2024-09-14 201821](https://github.com/user-attachments/assets/fa78194b-8486-4a09-8931-d660f40ff6ec)

 
![Screenshot 2024-09-14 201739](https://github.com/user-attachments/assets/a59e02fc-c34e-43f7-867e-3e6d885c8d53)




### Updating Design Variables, Including Custom LEF, and Running Synthesis for `picorv32a`



```bash
# Prep design to update variables with a custom tag and overwrite the previous setup
prep -design picorv32a -tag 09-09_06-53 -overwrite

# Additional commands to include newly added LEF files into OpenLANE flow
set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
add_lefs -src $lefs

# Display the current value of the SYNTH_STRATEGY variable
echo $::env(SYNTH_STRATEGY)

# Set a new value for the SYNTH_STRATEGY variable
set ::env(SYNTH_STRATEGY) "DELAY 3"

# Display the current value of the SYNTH_BUFFERING variable to check whether it's enabled
echo $::env(SYNTH_BUFFERING)

# Display the current value of the SYNTH_SIZING variable
echo $::env(SYNTH_SIZING)

# Set a new value for the SYNTH_SIZING variable
set ::env(SYNTH_SIZING) 1

# Display the current value of the SYNTH_DRIVING_CELL variable to check if it's the proper cell
echo $::env(SYNTH_DRIVING_CELL)

# Now that the design is prepped and ready, run synthesis using the following command
run_synthesis
``` 

![Screenshot 2024-09-14 202728](https://github.com/user-attachments/assets/c5444d99-cc48-4855-9ea3-505a2b192b2f)

![Screenshot 2024-09-14 202834](https://github.com/user-attachments/assets/df9aa502-c7d6-4bd0-8225-966a5d439cc1)


![Screenshot 2024-09-14 203121](https://github.com/user-attachments/assets/9b3b4596-7d8d-480c-92bf-2961db9ce1ba)

![Screenshot 2024-09-14 203209](https://github.com/user-attachments/assets/cdf6c8e6-c099-4438-9d91-2a21625755b3)


![Screenshot 2024-09-14 203237](https://github.com/user-attachments/assets/a13d36f0-3c6d-42d7-83f7-1ed12edf896e)


![Screenshot 2024-09-14 203245](https://github.com/user-attachments/assets/9452a276-b8e9-4c31-928d-e33e80976fe1)

### Running Floorplan After Synthesis Acceptance of Custom Inverter



```bash
# Now we can run the floorplan
run_floorplan
``` 

![Screenshot 2024-09-14 203459](https://github.com/user-attachments/assets/11e276d4-1cbe-4b18-bee7-6e098c1a26cf)

If you encounter errors with the `run_floorplan` command,  use the individual commands from the `floorplan.tcl` script to diagnose and address the issues. Here are the commands to run sequentially based on the information provided:

```bash
# Initialize the floorplan setup
init_floorplan

# Place the input/output (IO) pins
place_io

# Apply tap and decap to the floorplan
tap_decap_or
```


![Screenshot 2024-09-14 203549](https://github.com/user-attachments/assets/a390dccf-ae4b-414b-9984-4f64592c98ef)

![Screenshot 2024-09-14 203717](https://github.com/user-attachments/assets/8eb226b9-b6ff-48d2-8e15-b89e0784cafa)


![Screenshot 2024-09-14 203741](https://github.com/user-attachments/assets/cf28e9e9-d3d2-47e3-9d0f-f4303f6da225)

Here is the command to run placement after completing the floorplan:

```bash
# Now we are ready to run placement
run_placement
```


![Screenshot 2024-09-14 203829](https://github.com/user-attachments/assets/f9932344-e336-4568-9419-482fc34ef4d7)


![Screenshot 2024-09-14 203958](https://github.com/user-attachments/assets/35dc6ba2-6302-480b-8b77-2fa8dde853ce)




1. Change the directory to the location of the generated placement `.def` file:
   ```bash
   cd Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/09-09_06-53/results/placement/
   ```

2. Load the placement `.def` file in the Magic tool:
   ```bash
   magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.placement.def &
   ```

![Screenshot 2024-09-14 214627](https://github.com/user-attachments/assets/0453fd4c-4a78-470e-adea-e9840cb8e578)

![Screenshot 2024-09-15 220127](https://github.com/user-attachments/assets/f7562ccd-2af2-443d-91a4-5688b737dc9c)


![Screenshot 2024-09-15 220214](https://github.com/user-attachments/assets/f8f61879-d442-4610-910d-498b4f915f1c)

![Screenshot 2024-09-15 220306](https://github.com/user-attachments/assets/bb34f7f4-60eb-40af-b8f7-91a22dfef985)



1. Change the directory to the OpenLANE flow directory:
   ```bash
   cd Desktop/work/tools/openlane_working_dir/openlane
   ```

2. 
   ```bash
   # alias docker='docker run -it -v $(pwd):/openLANE_flow -v $PDK_ROOT:$PDK_ROOT -e PDK_ROOT=$PDK_ROOT -u $(id -u $USER):$(id -g $USER) efabless/openlane:v0.21'
   docker
   ```


1. **Invoke the OpenLANE flow in interactive mode**:

   ```bash
   ./flow.tcl -interactive
   ```

2. **Load the required OpenLANE package**:
   :
   ```tcl
   package require openlane 0.9
   ```

3. **Prepare the design**:
   
   ```tcl
   prep -design picorv32a
   ```

4. **Include newly added LEF files**:
  
   ```tcl
   set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
   add_lefs -src $lefs
   ```

5. **Set the new value for `SYNTH_SIZING`**:
   is:
   ```tcl
   set ::env(SYNTH_SIZING) 1
   ```

6. **Run synthesis**:
 
   ```tcl
   run_synthesis
   ```
![Screenshot 2024-09-15 225249](https://github.com/user-attachments/assets/effd6836-ca69-484a-b3f4-48152ed090bf)
Newly created `pre_sta.conf` for STA analysis in `openlane` directory
![Screenshot 2024-09-16 120759](https://github.com/user-attachments/assets/b15d47e9-5e69-4737-be6a-3b41b4e6d61d)

Newly created `my_base.sdc` for STA analysis in` openlane/designs/picorv32a/src` directory based on the file `openlane/scripts/base.sdc

![Screenshot 2024-09-16 120712](https://github.com/user-attachments/assets/22810c78-e98f-458b-b547-262d9b1ca496)

### Clock Tree Synthesis

### Steps:

1. **Navigate to the OpenLane Directory:**

 
   
   ```bash
   cd ~/Desktop/work/tools/openlane_working_dir/openlane
   ```

2. **Run OpenSTA with the `pre_sta.conf` Script:**



1. **Re-prep the design to update variables**:
   This command preps the design again with a specific tag (`09-09_06-53`) and overwrites the existing files:
   ```tcl
   prep -design picorv32a -tag 09-09_06-53 -overwrite
   ```

2. **Include newly added LEF files**:
   After prepping, include the updated LEF files (if any) into the OpenLANE flow:
   ```tcl
   set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
   add_lefs -src $lefs
   ```

3. **Set new values for synthesis strategy and sizing**:
   Set a new synthesis strategy (e.g., prioritize delay with a factor of 3):
     ```tcl
     set ::env(SYNTH_STRATEGY) "DELAY 3"
     ```
    Set the synthesis sizing:
     ```tcl
     set ::env(SYNTH_SIZING) 1
     ```

4. **Run synthesis**:
   After prepping and updating variables, rerun the synthesis:
   ```tcl
   run_synthesis
   ```

5. **Run floorplanning steps (init floorplan, place I/O, tap, decap)**:
   The following commands are internally sourced when you run the `run_floorplan` command:
   ```tcl
   init_floorplan
   place_io
   tap_decap_or
   ```

6. **Run placement**:
   After floorplanning, you can proceed with the placement:
   ```tcl
   run_placement
   ```

7. **Unset `LIB_CTS` environment variable if there is an error**:
   In case you encounter an error related to clock tree synthesis (CTS), you can unset the `LIB_CTS` variable:
   ```tcl
   unset ::env(LIB_CTS)
   ```

8. **Run clock tree synthesis (CTS)**:
   Finally, after placement, proceed to run CTS:
   ```tcl
   run_cts
   ```
![Screenshot 2024-09-16 151855](https://github.com/user-attachments/assets/f8e427c1-baac-4b44-806c-0d7283f5bbc8)

![Screenshot 2024-09-16 151914](https://github.com/user-attachments/assets/eba10e09-f26d-457c-8dca-4cc4579f4683)

![Screenshot 2024-09-16 151944](https://github.com/user-attachments/assets/34c7880d-d8af-4f1c-b2c0-4cbbfc85e5ab)

![Screenshot 2024-09-16 152008](https://github.com/user-attachments/assets/b88fb9a7-530a-42c4-a0eb-66347374705a)


![Screenshot 2024-09-16 152032](https://github.com/user-attachments/assets/caadf813-ffff-43a5-9ba5-b532a2dba607)

![Screenshot 2024-09-16 152133](https://github.com/user-attachments/assets/e23ccb2b-9662-4b65-8cc0-7eb42d5d0105)

![Screenshot 2024-09-16 152243](https://github.com/user-attachments/assets/dc3c68c2-5cbd-49b0-bb71-f253e2fb294a)

**Post-CTS OpenROAD timing analysis.**

Here’s the complete set of commands for running OpenROAD and performing the specified tasks:

```bash
# Command to run OpenROAD tool
openroad

# Reading LEF file
read_lef /openLANE_flow/designs/picorv32a/runs/09-09_05-53/tmp/merged.lef

# Reading DEF file
read_def /openLANE_flow/designs/picorv32a/runs/09-09_05-53/results/cts/picorv32a.cts.def

# Creating an OpenROAD database to work with
write_db pico_cts.db

# Loading the created database in OpenROAD
read_db pico_cts.db

# Read netlist post CTS
read_verilog /openLANE_flow/designs/picorv32a/runs/09-09_05-53/results/synthesis/picorv32a.synthesis_cts.v

# Read library for design
read_liberty $::env(LIB_SYNTH_COMPLETE)

# Link design and library
link_design picorv32a

# Read in the custom SDC we created
read_sdc /openLANE_flow/designs/picorv32a/src/my_base.sdc

# Setting all clocks as propagated clocks
set_propagated_clock [all_clocks]

# Check syntax of 'report_checks' command
help report_checks

# Generating custom timing report
report_checks -path_delay min_max -fields {slew trans net cap input_pins} -format full_clock_expanded -digits 4

# Exit to OpenLANE flow
exit
```
![Screenshot 2024-09-16 152316](https://github.com/user-attachments/assets/447d5981-f0c6-4a79-be18-0451de108c2c)

![Screenshot 2024-09-16 152856](https://github.com/user-attachments/assets/d05dd76d-b59c-4e21-8df3-4f58ff1376e1)

![Screenshot 2024-09-16 152908](https://github.com/user-attachments/assets/1c20b1b2-421a-4700-ad41-f7b1b53395e6)



![Screenshot 2024-09-16 152926](https://github.com/user-attachments/assets/78892a9f-eb27-49d8-8df6-be2d442fc6df)

**Post-CTS OpenROAD timing analysis by removing 'sky130_fd_sc_hd__clkbuf_1' cell from clock buffer list variable 'CTS_CLK_BUFFER_LIST'.**

Commands to be run in OpenLANE flow to do OpenROAD timing analysis after changing `CTS_CLK_BUFFER_LIST`

Here are the commands formatted for you to copy and paste:

```bash
# Checking current value of 'CTS_CLK_BUFFER_LIST'
echo $::env(CTS_CLK_BUFFER_LIST)

# Removing 'sky130_fd_sc_hd__clkbuf_1' from the list
set ::env(CTS_CLK_BUFFER_LIST) [lreplace $::env(CTS_CLK_BUFFER_LIST) 0 0]

# Checking current value of 'CTS_CLK_BUFFER_LIST'
echo $::env(CTS_CLK_BUFFER_LIST)

# Checking current value of 'CURRENT_DEF'
echo $::env(CURRENT_DEF)

# Setting def as placement def
set ::env(CURRENT_DEF) /openLANE_flow/designs/picorv32a/runs/24-03_10-03/results/placement/picorv32a.placement.def

# Run CTS again
run_cts


# Checking current value of 'CTS_CLK_BUFFER_LIST'
echo $::env(CTS_CLK_BUFFER_LIST)

# Command to run OpenROAD tool
openroad

# Reading LEF file
read_lef /openLANE_flow/designs/picorv32a/runs/24-03_10-03/tmp/merged.lef

# Reading DEF file
read_def /openLANE_flow/designs/picorv32a/runs/24-03_10-03/results/cts/picorv32a.cts.def

# Creating an OpenROAD database to work with
write_db pico_cts1.db

# Loading the created database in OpenROAD
read_db pico_cts.db

# Read netlist post CTS
read_verilog /openLANE_flow/designs/picorv32a/runs/24-03_10-03/results/synthesis/picorv32a.synthesis_cts.v

# Read library for design
read_liberty $::env(LIB_SYNTH_COMPLETE)

# Link design and library
link_design picorv32a

# Read in the custom SDC we created
read_sdc /openLANE_flow/designs/picorv32a/src/my_base.sdc

# Setting all clocks as propagated clocks
set_propagated_clock [all_clocks]

# Generating custom timing report
report_checks -path_delay min_max -fields {slew trans net cap input_pins} -format full_clock_expanded -digits 4

# Report hold skew
report_clock_skew -hold

# Report setup skew
report_clock_skew -setup

# Exit to OpenLANE flow
exit

# Checking current value of 'CTS_CLK_BUFFER_LIST'
echo $::env(CTS_CLK_BUFFER_LIST)

# Inserting 'sky130_fd_sc_hd__clkbuf_1' to first index of list
set ::env(CTS_CLK_BUFFER_LIST) [linsert $::env(CTS_CLK_BUFFER_LIST) 0 sky130_fd_sc_hd__clkbuf_1]

# Checking current value of 'CTS_CLK_BUFFER_LIST'
echo $::env(CTS_CLK_BUFFER_LIST)
```

![Screenshot 2024-09-16 155018](https://github.com/user-attachments/assets/4468fe4d-9a2c-4dd3-bea8-0b5a8ddef63a)

![Screenshot 2024-09-16 155030](https://github.com/user-attachments/assets/60dc0ff6-6318-4e1f-934c-d1f610ccf935)

![Screenshot 2024-09-16 155628](https://github.com/user-attachments/assets/877a8b9e-ce79-481f-b000-b564a2479484)

![Screenshot 2024-09-16 155653](https://github.com/user-attachments/assets/8286c8ef-821a-4278-a285-cfad5d04e882)

![Screenshot 2024-09-16 155711](https://github.com/user-attachments/assets/7ec327ef-b7b7-4f09-986c-ed902fcca25e)

![Screenshot 2024-09-16 155834](https://github.com/user-attachments/assets/ffff6173-9ced-4a19-b55a-9a4efb1bb06e)

### DAY FIVE

**Theory**

Here’s a suitable header for your commands to generate the Power Distribution Network (PDN) and explore the PDN layout using OpenLANE:

---

# Power Distribution Network (PDN) Generation and Layout Exploration in OpenLANE


###  **Navigate to the OpenLane Flow Directory**:
   
   
   ```bash
   cd ~/Desktop/work/tools/openlane_working_dir/openlane
   ```

### **Run the Docker Command**:
   Since we have aliased the Docker command with the environment setup, we can simply run the following:

   ```bash
   docker
   ```





###  Enter OpenLANE Flow Interactive Mode
```bash
./flow.tcl -interactive
```


---

### Load Required OpenLANE Package
```bash
package require openlane 0.9
```


---

###  Prepare the Design
```bash
prep -design picorv32a
```

---

### Add New LEF Files
```bash
set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
add_lefs -src $lefs
```

---

### : Set Synthesis Strategy
```bash
set ::env(SYNTH_STRATEGY) "DELAY 3"
```


---

###  Set Synthesis Sizing
```bash
set ::env(SYNTH_SIZING) 1
```


---

###  Run Synthesis
```bash
run_synthesis
```

---

### Initialize Floorplan
```bash
init_floorplan
```


---

###  Place I/O Pads
```bash
place_io
```


---

###  Insert Decap and Tap Cells
```bash
tap_decap_or
```


---

### Run Placement
```bash
run_placement
```


---

### : Handle CTS Library Issue (Optional)

```bash
unset ::env(LIB_CTS)
```


---

###  Run Clock Tree Synthesis (CTS)
```bash
run_cts
```


---

###  Generate Power Distribution Network (PDN)
```bash
gen_pdn
```
---

![Screenshot 2024-09-16 223337](https://github.com/user-attachments/assets/9a7ba036-bd7a-40d3-ac89-7fb5cd2c4218)

![Screenshot 2024-09-16 223436](https://github.com/user-attachments/assets/a6a02e5b-b4cb-46aa-9efc-15644ddab22c)

![Screenshot 2024-09-16 223526](https://github.com/user-attachments/assets/209845ed-361d-48a6-8fb3-9fd4e14149d3)

![Screenshot 2024-09-16 223541](https://github.com/user-attachments/assets/9c4c1ee4-5c0f-4312-8f73-28039cbdbeff)

![Screenshot 2024-09-16 223601](https://github.com/user-attachments/assets/d33c997c-2818-41cb-b1b4-e45c1ec3e0b9)

![Screenshot 2024-09-16 223619](https://github.com/user-attachments/assets/4f3dbc44-f583-4d60-a876-2856e46c2e9e)

![Screenshot 2024-09-16 223646](https://github.com/user-attachments/assets/f475d5ce-c912-4116-b91a-9e6f6f892715)

![Screenshot 2024-09-16 223720](https://github.com/user-attachments/assets/19ba6b4e-ce7a-4c4b-a8fc-a8d3ea1fb294)

![Screenshot 2024-09-16 223826](https://github.com/user-attachments/assets/9b727280-a259-4c0a-a230-2be6ecd609a1)

![Screenshot 2024-09-16 223838](https://github.com/user-attachments/assets/80c78fde-800f-48eb-9e0f-6b90c444f017)

### Commands to load PDN def in magic in another terminal

### Change Directory to the PDN DEF File Location
```bash
cd Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/09-09_06-53/tmp/floorplan/
```
This command navigates to the directory where the PDN DEF (Design Exchange Format) file is located, so you can load it in the Magic tool.

---

###  Load PDN DEF File into Magic Tool
```bash
magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read 18-pdn.def &
```
![Screenshot 2024-09-17 110908](https://github.com/user-attachments/assets/f6e8473b-1543-4e2c-89ac-97cf9450bf8e)

![Screenshot 2024-09-17 111448](https://github.com/user-attachments/assets/3ff2398e-6613-476d-afe1-5de0ea6dcea6)

![Screenshot 2024-09-17 110927](https://github.com/user-attachments/assets/bd47fec8-e62f-42a0-b5fd-3b635ebd203d)

![Screenshot 2024-09-17 110949](https://github.com/user-attachments/assets/fe78d74d-f9b6-48ac-a94d-2c1a936906d5)


![Screenshot 2024-09-17 111011](https://github.com/user-attachments/assets/643d34ae-4a5a-4dcc-b1a8-f65ef1cdaeea)


![Screenshot 2024-09-17 111044](https://github.com/user-attachments/assets/818d0385-26d1-4a01-a2b8-c93fbf332a50)


![Screenshot 2024-09-17 111228](https://github.com/user-attachments/assets/7b5d1f1c-f2aa-4cbf-8a80-031c03970797)


![Screenshot 2024-09-17 111359](https://github.com/user-attachments/assets/47d92a43-b3fb-4e9a-b000-26cfa088958a)

### Perfrom detailed routing using TritonRoute and explore the routed layout.

###  Check Value of 'CURRENT_DEF'
```bash
echo $::env(CURRENT_DEF)
```


---

### Check Value of 'ROUTING_STRATEGY'
```bash
echo $::env(ROUTING_STRATEGY)
```


---

### Perform Detailed Routing with TritonRoute
```bash
run_routing
```
![Screenshot 2024-09-17 105811](https://github.com/user-attachments/assets/fdded96f-a7b3-47cc-a0ae-653c9a204393)

![Screenshot 2024-09-17 105847](https://github.com/user-attachments/assets/cab70456-8d93-47c3-855a-c6a2cf7cd8d1)

![Screenshot 2024-09-17 110403](https://github.com/user-attachments/assets/5cc9dff4-ef02-4f8a-aa70-6c0bc3f00b87)


**Commands to load routed def in magic in another terminal**

```bash
# Load the Routed DEF into Magic for Exploration

# Step 1: Change directory to the path containing the routed DEF
cd Desktop/work/tools/openlane_working_dir/openlane/designs/picorv32a/runs/17-09_05-07/results/routing/

# Step 2: Command to load the routed DEF into Magic tool
magic -T /home/vsduser/Desktop/work/tools/openlane_working_dir/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.lef def read picorv32a.def &
```

![Screenshot 2024-09-17 111812](https://github.com/user-attachments/assets/cbaa299d-0388-4587-aa71-a8a725acea7a)

![Screenshot 2024-09-17 110602](https://github.com/user-attachments/assets/89f51158-629f-4422-b5ea-df13152795f6)

![Screenshot 2024-09-17 110622](https://github.com/user-attachments/assets/7a12c90c-8680-46b9-8d3c-526fb0ca8ca7)

![Screenshot 2024-09-17 110646](https://github.com/user-attachments/assets/273456b8-309e-49fa-bfa0-2badffcb51a4)

![Screenshot 2024-09-17 112056](https://github.com/user-attachments/assets/c5e922b3-1adf-45c6-8499-06cd25a366b5)

![Screenshot 2024-09-17 112014](https://github.com/user-attachments/assets/d4dee965-fe44-410f-bca8-788a99420713)


**Fast route guide present in `openlane/designs/picorv32a/runs/17-09_05-07/tmp/routing` directory**


![Screenshot 2024-09-17 114109](https://github.com/user-attachments/assets/bdc160b8-1e07-40d4-8e76-f30233cd7795)

 **Post-Route OpenSTA timing analysis with the extracted parasitics of the route**

Commands to be run in OpenLANE flow to do OpenROAD timing analysis with integrated OpenSTA in OpenROAD



###  Run the OpenROAD Tool
```bash
openroad
```


---

### Read the LEF File
```bash
read_lef /openLANE_flow/designs/picorv32a/runs/17-09_05-07/tmp/merged.lef
```


---

###  Read the DEF File
```bash
read_def /openLANE_flow/designs/picorv32a/runs/17-09_05-07/results/routing/picorv32a.def
```


---

###  Create an OpenROAD Database
```bash
write_db pico_route.db
```

---

### Load the Created Database
```bash
read_db pico_route.db
```


---

###  Read Netlist Post-CTS
```bash
read_verilog /openLANE_flow/designs/picorv32a/runs/17-09_05-07/results/synthesis/picorv32a.synthesis_preroute.v
```


---

###  Read the Liberty File (Library)
```bash
read_liberty $::env(LIB_SYNTH_COMPLETE)
```


---

### Link the Design and Library
```bash
link_design picorv32a
```


---

###  Read the Custom SDC File
```bash
read_sdc /openLANE_flow/designs/picorv32a/src/my_base.sdc
```


---

###  Set All Clocks as Propagated Clocks
```bash
set_propagated_clock [all_clocks]
```


---

###  Read the SPEF File
```bash
read_spef /openLANE_flow/designs/picorv32a/runs/17-09_05-07/results/routing/picorv32a.spef
```


---

###  Generate a Custom Timing Report
```bash
report_checks -path_delay min_max -fields {slew trans net cap input_pins} -format full_clock_expanded -digits 4
```

---

###  Exit OpenROAD
```bash
exit
```

---

![Screenshot 2024-09-17 115236](https://github.com/user-attachments/assets/855cf700-bc66-4d3d-ac95-01e9285388e5)


![Screenshot 2024-09-17 115254](https://github.com/user-attachments/assets/d45160e2-8a59-4ef6-bb24-cc0c2d406bc3)


![Screenshot 2024-09-17 115305](https://github.com/user-attachments/assets/99ad0f02-98ea-4eb9-845d-40865ff2c5af)


