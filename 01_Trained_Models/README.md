## Model Trained

Six deep learning models were developed, each trained on a unique dataset configuration as shown in Figure [3]. To prevent overfitting, datasets were split into 70% training, 20% validation, and 10% test segments, with the latter consisting of previously unseen images. Images were uniformly resized to 640 pixels squared, and augmented with noise (1%), brightness variations (±14%), and rotations (±12%).

Training occurred on Google Cloud Platform™ using NVIDIA® Tesla T4 and Volta V100 GPUs, employing AdamW optimizer with a 0.001 learning rate and 16 batch size, beginning with pre-trained weights. The best model for each configuration was selected after 100 epochs based on validation metrics, aiming for consistently low losses. The entire training effort for the six models took approximately 40 hours.

## Figures

<p align="center">
  <img src="02_Figures/Fig_422b_Real_Val_Images_examples.png" alt="Model Test">
  <br>
  <em>Fig1.  The REAL(real_val) model is capable of accurately identifying and classifying objects within six real airport images. Source: Authors.</em>
</p>


<p align="center">
  <img src="02_Figures/Fig_324a_Figx_Hybrid Dataset.png" alt="Dataset generation">
  <br>
  <em>Fig2. Hybrid datasets formation, combining real and synthetic images in 10% (*) and 20% (**) mixes, resulting in four distinct datasets. Source: Authors</em>
</p>

<p align="center">
  <img src="https://github.com/astromaf/Synth_Airport_Taxii/blob/main/02_Figures/Fig_324b_Comparaci%C3%B3n_6_Datasets.png" alt="Datset comparison">
  <br>
  <em>Fig3.  Class balance between (a) initial datasets, (b) 10% mix, and (c) 20% mix. Source: Authors.</em>
</p>

---

## Download:
Due to the size limitations of GitHub repositories, the trained models are available for download at the following link: https://drive.google.com/file/d/1s2PuU6891GdRzgAjii16_5z75O9yisT0/view?usp=sharing

*By Miguel Ángel de Frutos Carro*

