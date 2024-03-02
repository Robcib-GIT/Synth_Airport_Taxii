# Validating Synthetic Data for Perception in Autonomous Airport Navigation Tasks

<p align="center">
  <em>Disclaimer: This project and all associated materials are currently under review for publication.</em>
</p>

**Authors:** Miguel Ángel de Frutos Carro, Carlos Cerdán Villalonga, and Antonio Barrientos.

**Affiliation:** Centro de Automática y Robótica (UPM-CSIC), Universidad Politécnica de Madrid - Consejo Superior de Investigaciones Científicas, 28006 Madrid, Spain.

---

## Abstract
Autonomous navigation within airport environments poses significant challenges, primarily due to the scarcity of accessible and labeled data for training autonomous systems. This study introduces an innovative approach to evaluate the performance of vision-based models trained on synthetic datasets. We conducted a comparative analysis of two datasets: a synthetic dataset that mirrors real airport scenarios, generated using Microsoft Flight Simulator 2020®, and a real-world dataset. The goal is to assess the effectiveness of simulated data in enhancing the training and validation processes for complex airport environments. Our methodology includes a comparative analysis using image processing techniques and object detection algorithms. The findings suggest that models trained on a mix of real and synthetic images perform better, showing improved adaptability and accuracy over those trained on a single dataset type. This research contributes significantly to the field of autonomous airport navigation, offering a cost-effective and practical solution to overcome dataset acquisition and algorithm validation challenges, thereby laying the groundwork for future advancements.

**Keywords:** *Autonomous vehicles, airport markings recognition, computer vision, object detection, hybrid dataset, game engine.*

---

## Figures

<p align="center">
  <img src="https://github.com/astromaf/Synth_Airport_Taxii/blob/main/02_Figures/GIF_test_MSFS_AA(dataset_real).gif" alt="Real Test Scenario">
  <br>
  <em>Fig1. MSFS_AA (dataset_real) - Real Test Scenario</em>
</p>

<p align="center">
  <img src="https://github.com/astromaf/Synth_Airport_Taxii/blob/main/02_Figures/GIF_test_REAL_AA(dataset_msfs).gif" alt="MSFS Test Scenario">
  <br>
  <em>Fig2. REAL_AA (dataset_msfs) - MSFS Test Scenario</em>
</p>

<p align="center">
  <img src="https://github.com/astromaf/Synth_Airport_Taxii/blob/main/02_Figures/Fig322a_clases.png" alt="Classes to be detected">
  <br>
  <em>Fig3. Classes to be detected: (a) “Taxiway Lane”, (b) “Vertical Sign”, (c) “Person”, (d) Airplane, (e) “Horizontal Sign”, (f) “Runway Limit”, and (g) “Ground Vehicle”. Source: Author composition.</em>
</p>

## License:
GPU v3.0: https://github.com/astromaf/Synth_Airport_Taxii/blob/main/LICENSE


*By Miguel Ángel de Frutos Carro*
