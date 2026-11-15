# Optimization of Artificial Intelligence (AI-Inference) on the "FPGA-Vision" Embedded Hardware for Automotive Applications

**Author:** Nassiri Ibrahim  
**Degree:** Master’s Degree in Computer Systems Engineering (ISI) — Option: Engineering of Intelligent Systems, Networks and Telecommunications (IISRT)  
**Institution:** Higher School of Management, Computer Science and Telecommunications (SUPMTI), Meknes, Morocco  
**Host Company:** 3D Smart Factory (Mohammedia, Morocco)  
**Submission Date:** July 9, 2025 (Report No. 26/2025)  

### Supervision & Jury
* **Academic Supervisor:** Prof. Tarik Hajji (ENSAM Meknes)
* **Industrial Supervisor:** Mr. Thierry Bertin (CEO, 3D Smart Factory)
* **Jury President / Examiner:** Prof. Zakaria Ait El Mouden (EST Meknes)
* **Reviewer (Rapporteur):** Prof. Noureddine El Harmouchi (SUPMTI Meknes)

---

## Abstract
This report presents my graduation project for my final year in Intelligent Computer Systems Engineering. It focuses on road sign detection, a vital component of autonomous driving systems. The project aims to develop robust and efficient methods for detecting road signs using computer vision techniques. 

The proposed approach trains a neural network model to recognize road signs from images captured by cameras mounted on vehicles; the model learns from a dataset of labeled images and adapts to varying environmental conditions. The report details the design and implementation of the neural network architecture, the training process, and the results of the experiments conducted to evaluate the model's performance. The study aims to contribute to the development of safer and more reliable autonomous driving systems, ultimately reducing the risk of accidents and improving road safety. It also compares the capabilities of Spiking Neural Networks (SNNs) in terms of energy and time consumption, highlighting areas that need improvement.

**Keywords:** Neural network, Machine learning, Training, Road signs, Field-Programmable Gate Array (FPGA)

---

## Technologies & Tools Used
* **Machine Learning & Training:** Python (Jupyter Notebook, Keras), GNU Octave
* **Neural Architectures:** Multi-Layer Perceptrons (MLP), Artificial Neural Networks (ANN), Spiking Neural Networks (SNN - Leaky Integrate-and-Fire)
* **Hardware Implementation:** VHDL, Intel Quartus Prime (Fixed-Point Arithmetic)
* **Target Hardware:** Altera Cyclone V FPGA (`5CEBA2F17C6`) via FPGA-Vision Remote Lab

---

## Repository Contents
* [`Nassiri_Ibrahim_Thesis_Report.pdf`](./Nassiri_Ibrahim_Thesis_Report.pdf) — Full End-of-Studies Project Report (English Version)
* `/src` — Source code for ANN/SNN training, model standardization, and VHDL hardware synthesis
