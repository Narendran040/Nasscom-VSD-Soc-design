# Nasscom-VSD-Soc-design
# Open source EDA tools 
https://github.com/kunalg123/vsdflow.git
# OpenLane
https://github.com/The-OpenROAD-Project/OpenLane.git
# Skywater 130 PDK
https://github.com/RTimothyEdwards/open_pdks.git

# Day one
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

### Flow:
   - **From the user’s perspective**: You use **Application Software**.
   - **System software** (the OS) manages the hardware and the applications.
   - **Compilers and assemblers** are used to transform high-level programming into a form the hardware can execute.
   - Ultimately, the **hardware** executes the instructions from the software.






 # Open-source digital ASIC design

![asic](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/ad469a48-3080-483d-9aa5-18ad3aa4497c)

# RTL2GDS flow

![rtl2gds](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/74dcce8e-1fd0-40a2-9535-cb254c1b72f9)

# OpenLane ASIC flow

![asic flow](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/6121eb04-ac55-498b-b9d1-d44ea569919a)

# Invoking Openlane and Design Preparation

```
make mount
./flow.tcl -interactive
package require openlane 0.9
prep -design picorv32
```

![sys](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/16a0bb2b-fb4e-495f-a381-f2a5c7d2ef8a)




# Day Two


# Height and Width of core and die


![flll](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/97004977-3bbe-44bd-ad2c-9c8ac3136935)

 
 
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
