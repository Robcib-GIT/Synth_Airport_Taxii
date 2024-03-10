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

---

## License:
GPU v3.0: https://github.com/astromaf/Synth_Airport_Taxii/blob/main/LICENSE

---

## References:
- Asobo Studio, & Xbox Game Studios. (2020). *Microsoft Flight Simulator 2020*. https://flightsimulator.com/
- Barresi, F. F., & Allasia, W. (2013). *Airport Markings Recognition for Automatic Taxiing*.
- Bauer, A., Trapp, S., Stenger, M., Leppich, R., Kounev, S., Leznik, M., Chard, K., & Foster, I. (2024). *Comprehensive Exploration of Synthetic Data Generation: A Survey*. http://arxiv.org/abs/2401.02524
- Coombes, M., Eaton, W., & Chen, W. H. (2017). *Machine Vision for UAS Ground Operations: Using Semantic Segmentation with a Bayesian Network classifier*. Journal of Intelligent and Robotic Systems: Theory and Applications, 88(2–4), 527–546. https://doi.org/10.1007/s10846-017-0542-5
- Cremona, J., Uzal, L., & Pire, T. (2022). *WGANVO: odometría visual monocular basada en redes adversarias generativas*. RIAI - Revista Iberoamericana de Automatica e Informatica Industrial, 19(2), 144–153. https://doi.org/10.4995/RIAI.2022.16113
- Dhulipudi, D. P., & Rajan, K. S. (2020). *Multiclass geospatial object detection using machine learning-aviation case study*. AIAA/IEEE Digital Avionics Systems Conference - Proceedings, 2020-Octob. https://doi.org/10.1109/DASC50938.2020.9256771
- Dosovitskiy, A., Ros, G., Codevilla, F., Lopez, A., & Koltun, V. (2017). *CARLA: An Open Urban Driving Simulator*. http://arxiv.org/abs/1711.03938
- Ducoffe, M., Carrere, M., Féliers, L., Gauffriau, A., Mussot, V., Pagetti, C., & Sammour, T. (2023). *LARD-Landing Approach Runway Detection-Dataset for Vision Based Landing*. https://www.youtube.com/user/TheGreatFlyer
- European RPAS Steering Group, Tech. Rep. (2013). *Roadmap for the integration of civil Remotely-Piloted Aircraft Systems into the European Aviation System*.
- Jocher, G., Chaurasia, A., & Qiu, J. (2023). *Ultralytics YOLOv8*. https://github.com/ultralytics/ultralytics
- Lee, S., & Seo, S. W. (2022). *Probabilistic context integration-based aircraft behaviour intention classification at airport ramps*. IET Intelligent Transport Systems, 16(6), 725–738. https://doi.org/10.1049/itr2.12167
- Lu, B., Coombes, M., Li, B., & Chen, W. H. (2016). *Improved situation awareness for autonomous taxiing through self-learning*. IEEE Transactions on Intelligent Transportation Systems, 17(12), 3553–3564. https://doi.org/10.1109/TITS.2016.2557588
- OneView, & Airbus Defence and Space Intelligence. (2021). *Can Synthetic Data Really Improve Algorithm Accuracy?* https://ai4.io/pdfs/OneView-Airbus-Ai4-Press-Release.pdf
- Rong, G., Shin, B. H., Tabatabaee, H., Lu, Q., Lemke, S., Možeiko, M., Boise, E., Uhm, G., Gerow, M., Mehta, S., Agafonov, E., Kim, T. H., Sterner, E., Ushiroda, K., Reyes, M., Zelenkovsky, D., & Kim, S. (2020). *LGSVL Simulator: A High Fidelity Simulator for Autonomous Driving*. http://arxiv.org/abs/2005.03778
- Ros, G., Sellart, L., Materzynska, J., Vazquez, D., & Lopez, A. M. (2016). *The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes*. 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 3234–3243. https://doi.org/10.1109/CVPR.2016.352
- Shaikh, M. Y., Petrunin, I., & Zolotas, A. (2023, January 23). *Self-supervised Obstacle Detection During Autonomous UAS Taxi Operations*. AIAA SCITECH 2023 Forum. https://doi.org/10.2514/6.2023-2672
- Shermeyer, J., Hossler, T., Van Etten, A., Hogan, D., Lewis, R., & Kim, D. (2020). *RarePlanes: Synthetic Data Takes Flight*. http://arxiv.org/abs/2006.02963
- Steininger, D., Kriegler, A., Pointner, W., Widhalm, V., Simon, J., & Zendel, O. (2023). *Towards Scene Understanding for Autonomous Operations on Airport Aprons* (pp. 153–169). https://doi.org/10.1007/978-3-031-27066-6_11
- Suder, J., Podbucki, K., Marciniak, T., & Dabrowski, A. (2021). *Low complexity lane detection methods for light photometry system*. Electronics (Switzerland), 10(14). https://doi.org/10.3390/electronics10141665
- Talwar, D., Guruswamy, S., Ravipati, N., & Eirinaki, M. (2020). *Evaluating Validity of Synthetic Data in Perception Tasks for Autonomous Vehicles*. Proceedings - 2020 IEEE International Conference on Artificial Intelligence Testing, AITest 2020, 73–80. https://doi.org/10.1109/AITEST49225.2020.00018
- Tomaszewska, J., Krzysiak, P., Zieja, M., & Woch, M. (2018). *STATISTICAL ANALYSIS OF GROUND-RELATED INCIDENTS AT AIRPORTS*. https://doi.org/10.5604/01.3001.0012.4369
- Xue, W., & Roy, C. J. (2020). *Heterogeneous computing of cfd applications on a cpu-gpu platform using mpi and openacc*. AIAA Scitech 2020 Forum, 1–12. https://doi.org/10.2514/6

---
*By Miguel Ángel de Frutos Carro, Carlos Cerdán Villalonga & Antonio Barrientos Cruz 2024*
