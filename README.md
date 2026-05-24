# TFM MuBiB – Emma Reig Martí

This repository contains the complete development of the **Final Project Master’s Thesis** of the [Master's Degree in Bioinformatics and Biostatistics] titled **An integrated workflow based on Artificial Intelligence for the Optimization of Docetaxel-loaded Polymeric Micelles**. The project focuses on the design of an EDA and pre-processing pipeline to optimize the formulation of Soluplus/TPGS MPMs loaded with DTX, conduct the Design of Experiments (DoE) usign different commercial DoE/AI-driven softwares, and compare their performance.
---

## Description

The main objectives of this project are:

- Execute experimental designs using commercial software models to define the design space for polymeric micelles formulations.
- Perform an exhaustive EDA using Python to identify patterns and errors, and ensure the integrity of raw experimental data before applying to the software.
- Develop a Python-based standardized pre-processing to handle Dynamic Light Scaterring (DLS) multimodality, implementing similarity metrics (such as the Crámer-von Mises distance) to transform complex distributions into scalar descriptors.
- Evaluate and compare predictive accuracy of the commercial DoE software.


---

## Repository Structure

The repository is organized as follows:

---

## Main scripts

- `preparacio_dataset.py` → Data preparation and preprocessing  
- `carregador_dades.py` → Data loading  
- `model.py` → Model definition  
- `entrenament.py` → Training pipeline  
- `configuracio.py` → Configuration settings  

---

## Installation

Clone the repository:

```bash
git clone https://github.com/emma-reig/TFM_MuBiB_Emma-Reig.git
cd TFM_MuBiB_Emma-Reig

---

## Author  
Emma Reig Martí

---

## License
This project has been developed for academic purposes.
