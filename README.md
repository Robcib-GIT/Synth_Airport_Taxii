# Validating Synthetic Data for Perception in Autonomous Airport Navigation Tasks

**Author:** *Miguel Ángel de Frutos Carro (c), Carlos Cerdán Villalonga, and Antonio Barrientos.*

**Affiliation:** *Centro de Automática y Robótica (UPM-CSIC), Universidad Politécnica de Madrid-Consejo Superior de Investigaciones Científicas, 28006 Madrid, Spain.*


**Abstract:** *Autonomous navigation within airport environments presents significant challenges, primarily due to the scarcity of accessible and labelled data for training autonomous systems. This study introduces an innovative approach to assess the performance of vision-based models trained on synthetic datasets. To this aim, we conducted a comparative analysis of two different datasets. On one hand, a synthetic dataset that mirrors real airport scenarios,  generated using the Microsoft Flight Simulator 2020® video game and, on the other hand, a real-world dataset. The objective is to evaluate the effectiveness of simulated data in improving the training and validation processes for complex airport environments. Our methodology includes a comparative analysis employing image processing techniques and object detection algorithms. The results indicate that models trained on a combination of real and synthetic images exhibit superior performance, demonstrating enhanced adaptability and accuracy compared to those trained exclusively on one type of dataset. This research makes a significant contribution to the field of autonomous airport navigation, offering a cost-effective and practical solution to overcome the challenges of dataset acquisition and algorithm validation, laying the groundwork for future advancements in the field.*

**Keywords:** *autonomous vehicles; airport markings recognition; computer vision; object detection; hybrid dataset; game engine.*

<p align="center">

![MSFS**(dataset_real)](https://github.com/astromaf/Synth_Airport_Taxii/blob/main/02_Figures/GIF_test_MSFS_AA(dataset_real).gif "Real Test")

*Fig1. MSFS_AA(dataset_real)*

![REAL**(dataset_msfs)](https://github.com/astromaf/Synth_Airport_Taxii/blob/main/02_Figures/GIF_test_REAL_AA(dataset_msfs).gif "MSFS Test")

*Fig2. REAL_AA(dataset_msfs)*


![](https://github.com/astromaf/Synth_Airport_Taxii/blob/main/02_Figures/Fig322a_clases.png)

*Fig3. Classes to be detected: (a)“Taxiway Lane”, (b) “Vertical sign”, (c) “Person”, (d) Airplane, (e) “Horizontal Sign”, (f)“Runway Limit”, and (g) “Ground Vehicle”. Source: Author composition.

## License:
GPU v3.0: https://github.com/astromaf/ramp_hand_signals_recognition/blob/master/LICENSE

*By Miguel Ángel de Frutos Carro*
