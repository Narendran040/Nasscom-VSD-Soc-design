# Nasscom-VSD-Soc-design

# Day one
<details>
 <summary> Inception of Open source EDA, Open Lane, SKY 130 PDK </summary>

 
 # Arduino Uno
 
![Screenshot 2024-05-13 223726](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/b44b49d0-d6d3-4b93-a380-5ee00caedcc5)


 # RISC-V Soc

Package, Chip, Pads, Core, Die, IP's

![Screenshot 2024-05-13 224428](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/665454e8-a7dc-414f-b957-2b2d2c083e8f)


 Introduction to RISC-V

RISC-V is an open-source instruction set architecture (ISA) known for its flexibility, modularity, and extensibility. Unlike proprietary architectures, RISC-V provides blueprint access, allowing customization for specific applications. Its adoption spans diverse industries, from embedded systems to high-performance computing and AI, due to cost-effective customization, innovation potential, and robust security. RISC-V is hailed as the future of processing, placing customizable technology in developers' hands.

https://users.sussex.ac.uk/~mfb21/compilers/slides/11-handout.pdf


 # Open-source digital ASIC design

![asic](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/ad469a48-3080-483d-9aa5-18ad3aa4497c)

# RTL2GDS flow

![rtl2gds](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/74dcce8e-1fd0-40a2-9535-cb254c1b72f9)

# OpenLane ASIC flow

![asic flow](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/6121eb04-ac55-498b-b9d1-d44ea569919a)

# Invoking Openlane and Design Preparation


![sys](https://github.com/Narendran040/Nasscom-VSD-Soc-design/assets/157210399/16a0bb2b-fb4e-495f-a381-f2a5c7d2ef8a)


</details>

# Day Two
<details>
 <summary>Floorplan</summary>

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

 </details>
<details>

<summary>Placement</summary>

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
1. Inputs: PDKs, DRC & LVS rules, SPICE models, libraries, user-defined specifications.
2. Design steps: Circuit design, Layout design (Art of layout Euler's path and stick diagram), Extraction of parasitics, Characterization (timing, noise, power).
3. Outputs: CDL (circuit description language), LEF, GDSII, extracted SPICE netlist (.cir), timing, noise and power .lib files

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

</details>
 

</details>
