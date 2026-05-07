# Hi there, I'm Mari Venkatesh M 👋

### 🚀 VLSI Aspirant | FPGA & Edge AI Enthusiast | ECE @ IIIT Sri City

I am a highly motivated Electronics and Communication Engineering undergraduate with a strong focus on digital logic design, hardware verification, and hardware-software co-design. I enjoy bridging the gap between theoretical algorithms and physical silicon, optimizing architectures for power, area, and speed.

* 🎓 **Education:** B.Tech in ECE, Indian Institute of Information Technology, Sri City (Expected May 2027)
* 🔬 **Current Focus:** RTL-to-GDSII flows, Asynchronous CDC, and deploying low-power Edge AI on FPGAs.
* 💡 **Leadership:** Lead of **ConnexIon (IoT Club)**, mentoring teams in autonomous robotics. 
* 🏆 **Achievements:** GATE 2026 (ECE) Qualified | FPGA Hackathon 2026 Poster Presenter.
* 📫 **Contact me:** [marivenkatesh610@gmail.com](mailto:marivenkatesh610@gmail.com) | [LinkedIn Profile](https://linkedin.com/in/mari-venkatesh-m)

---

### 🛠️ Technical Arsenal

* **Hardware Description Languages:** Verilog, SystemVerilog
* **EDA & Simulation:** Cadence (Virtuoso, Xcelium, Genus, Innovus), Xilinx Vivado, Vitis HLS, ModelSim, HSPICE
* **Programming & Scripting:** C, C++, Python (TensorFlow, librosa, Matplotlib)
* **Hardware Platforms:** Zynq-7000 SoC Series, Digilent ZedBoard, Zybo
* **Hardware Prototyping:** Autodesk EAGLE (PCB Design)

---

### 💻 Featured Hardware & VLSI Projects

#### 1. RTL-to-GDSII: Telemetry-Integrated AXI Bridge for CDC
*Engineered a complete physical design flow on a 90nm node using Cadence tools.*
* Architected a 32-bit AXI4 Clock Domain Crossing (CDC) bridge utilizing asynchronous FIFOs.
* Synthesized an ultra-low-power gate-level netlist (~1.03 mW) in **Cadence Genus**.
* Executed floorplanning, CTS, and routing in **Cadence Innovus**, achieving zero setup/hold violations (+17.156 ns WNS) and a tape-out ready GDSII stream.

#### 2. FPGA Edge AI: Siren Detection Accelerator
*Hardware-software co-design for smart traffic management deployed on a Zynq-7020 SoC.*
* Trained and fully quantized a 1D-CNN to INT8, completely eliminating floating-point operations.
* Generated a custom IP via **Vitis HLS**, engineering a local "BRAM Shelf" to prevent AXI pipeline stalls.
* Achieved an end-to-end inference latency of 31.00 µs while drawing less than 0.07 W of Programmable Logic power.

#### 3. 90nm Custom IC: TSPC D-Flip Flop
*Transistor-level custom analog/mixed-signal design.*
* Designed a True Single-Phase Clock (TSPC) D-Flip Flop in **Cadence Virtuoso** to mitigate clock skew and minimize distribution area.
* Validated Clock-to-Q robustness across 36 extreme PVT corners, achieving 250 MHz operation at 1.242 µW.
* Delivered a 100% DRC/LVS clean physical layout, utilizing Quantus QRC for accurate parasitic extraction.

#### 4. Data Transfer FSM: Dual-Port RAM Controller
*Sequential logic design and asynchronous memory interfacing.*
* Developed a **Verilog FSM** to manage data synchronization between two dual-port RAM modules.
* Engineered real-time data width conversion logic to read sequential 8-bit inputs and output synchronized 16-bit words.

#### 5. UrbanSound8K Pattern Recognition Pipeline
*Proving classical ML efficiency over Deep Learning baselines.*
* Built a comprehensive Python audio feature extraction engine (`librosa`) to pull 65+ spectral and temporal features.
* Designed and optimized an SVM Classifier via Grid Search, achieving 86.57% accuracy and demonstrating the superiority of meticulous feature engineering over raw deep learning for this dataset.

#### 6. Full-Wave Precision Rectifier PCB
*End-to-end custom analog hardware prototyping.*
* Designed a dual-layer precision rectifier using an LM358D op-amp topology in **Autodesk EAGLE** to bypass standard diode forward voltage drops.
* Routed a dedicated ground plane, resolved all ERC/DRC constraints, and generated production-ready Gerber and Excellon drill files.

---
⚡ *“Hardware is just software crystallized.”*
