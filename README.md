  # Nasscom-VSD-Soc-design
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

![Screenshot 2024-09-14 154823](https://github.com/user-attachments/assets/306b933a-6991-4e1c-8da8-02553f6b2861)



> Create port definition

In the Magic Layout window, first source the .mag file for the design . Then Edit >> Text which opens up a dialogue box.


![D4 1](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/4e927615-1770-4ad6-b4a2-1c822deab5be)

> LEF extraction can be carried out in tkcon:


![D4 3](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/a67cdd27-f8e0-4a43-a591-b353b41f8eb1)

> Integrate the standard cell in the OpenLANE flow

```
./flow.tcl -interactive
package require openlane 0.9
prep -design picorv32 -tag RUN_2024.05.18_15.54.24 -overwrite
set lefs [glob $::env(DESIGN_DIR)/src/*.lef]
add_lefs -src $lefs
run_synthesis
```

![D4 8](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/0dc8b8c5-3c31-4260-a318-6c12f5c1dfeb)


![Screenshot 2024-05-21 214025](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/bdd8de27-b1dd-43c7-b407-1a7f023961ff)


![D4 6](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/06c594b1-0c3b-48d7-a063-f9032d0e243d)


![D4 7](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/7546a4a8-3d37-4221-ba12-1b63d78e39ec)






 # Day Five 



  # Power Distribution Network generation
  Power Distribution Network generation is not a part of the floorplan run in OpenLANE. PDN must be generated after CTS and post-CTS STA analyses
  
   ```
  gen_pdn
  ```


![gen_pdn](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/aae3332e-ebef-42ea-ba91-f704fa866ee3)

# Routing


   
 </details>
</details>
