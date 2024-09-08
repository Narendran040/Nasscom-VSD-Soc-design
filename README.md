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



The `libs.tech` directory contains technology-specific files that are essential for the design, simulation, and verification of ICs using the Skywater 130nm process. The directory you’ve shown contains folders for various tools such as `magic`, `ngspice`, and others, each tailored to work with the Sky130 PDK. Here’s a detailed breakdown of these tools and their roles:

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
   - **Files**: Contains templates, device symbols, and configuration files that help in drawing schematics according to the Sky130 process standards.

---

### 9. **`xschem`**:
   - **Purpose**: `xschem` is a schematic capture tool, often used in analog and mixed-signal design.
   - **Files**: This folder likely includes Sky130-specific device libraries, symbols, and configuration files, allowing `xschem` to be used for designing circuits at the schematic level with Skywater’s 130nm PDK.
</details>
     
<details>
  <summary>
 libs.ref
  </summary>



The `libs.ref` directory contains the reference libraries, which are pre-designed, pre-characterized standard cells, memory blocks, and I/O libraries used in the design of integrated circuits using the Skywater 130nm process. These libraries are crucial for digital logic design and are typically used in synthesis, place-and-route, simulation, and verification stages of the design flow. Here's a breakdown of the contents based on the structure you've provided:

---

### 1. **`sky130_fd_io`**:
   - **Purpose**: Contains the I/O library cells for the Skywater 130nm process.
   - **Files**: This includes I/O cells that handle interfacing between the chip and the external environment. These cells may include features like voltage level shifting, ESD protection, and signal buffering.
   - **Use**: Primarily used in the design's input/output pad ring, allowing signals to safely enter and exit the chip.

---

### 2. **`sky130_fd_pr`**:
   - **Purpose**: Likely contains the power-related cells for power distribution and protection within the chip.
   - **Files**: May include power rings, power pads, ground pads, and other cells that handle power and ground distribution across the chip.
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

### 5. **`sky130_fd_sc_hs`** (High Speed Standard Cells):
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
   - **Purpose**: Medium speed standard cells that balance power, performance, and area.
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

  ``run_synthesis``

 

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

Utilisation Factor = (4 sq.units)/(8 sq.units) = 0.5

Aspect Ratio=(2 units)/(4 units) = 0.5.The core is in a rectangular shape 


</details>



# Practical Section-2
> To run the picorv32a floorplan in openLANE:

```
 run_floorplan
 ```

 ![image](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/6ce45bab-2fd5-44ee-9c8f-088898dbc98e)

 > To view the floorplan, Magic is invoked after moving to the results/floorplan directory:
 ```
 magic -T /home/narendran/OpenLane/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.max.lef def read picorv32.def &
 ```

![Screenshot 2024-05-18 210345](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/261e5630-a89b-4951-8f43-4a04d74faaf3)

 

# Placement run on OpenLANE & view in Magic
```
run_placement
```


![rp](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/8505d9da-2085-4548-879c-f925faab28c4)



>To view the placement, Magic is invoked after moving to the results/placement directory:

```
magic -T /home/narendran/OpenLane/pdks/sky130A/libs.tech/magic/sky130A.tech lef read ../../tmp/merged.max.lef def read picorv32.def &
```


![pl2](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/f7f3d78c-792e-47f7-a0b1-4a3929b89476)

# Observing Standard Cell Placement

![fll1](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/9ed3d631-ef2f-4696-b354-21694e9f8c3d)

![fll2](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/8ebe303f-1750-4910-aa27-93cff1ff9b8d)

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

 # Inverter Standard cell Layout
 The inverter magic file is sourced from vsdstdcelldesign by cloning it within the openlane_working_dir/open lane directory as follows:
 ```
git clone https://github.com/nickson-jose/vsdstdcelldesign
```
> Invoking sky_inv.mag using Magic

```
magic -T sky130A.tech sky130_inv.mag &
```

![Cmos](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/5c61f265-58fa-40bc-91ef-9d3ad9379cc7)

![cmos 2](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/aab01056-6e53-4ee4-9f95-575ea6ad5bee)

# Spice extraction

```
extract all
ext2spice cthresh 0 rethresh 
ext2spice
```
![sp](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/23ab1a2f-23c9-486e-bd2b-500aa142e819)





 # Day Four
 

 
  A requirement for ports as specified in tracks.info is that they should be at the intersection of horizontal and vertical tracks. The CMOS Inverter ports A and Y are on the li1 layer. It needs to be ensured that they're on the intersection of horizontal and vertical tracks. We access the tracks.info 
  
  ```
  vim tracks.info
  ```

  ![vim](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/42420742-084e-4fc6-921f-e8eed7e5b8aa)

  > Grid spacing using Magic


  To ensure that ports lie on the intersection point, the grid spacing in Magic (tkcon) must be changed to the li1 X and li1 Y values. Convergence of grid and tracks can be achieved using the following command:
  
  ```
  grid 0.46um 0.34um 0.23um 0.17um
  ```

![Screenshot 2024-05-21 201420](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/53c130bd-1b86-412f-ab3d-7e8fa47429c3)

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
