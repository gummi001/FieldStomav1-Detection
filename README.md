# FieldStomav1 Detection

## Introduction
This repository contains the FieldStomav1 model for detecting stomata in corn using high-resolution field microscopy and deep learning. The model is implemented using Detectron2's Mask R-CNN framework with a ResNet-101 backbone, which allows for precise segmentation and detection of stomatal structures.

## Model Usage
To use the FieldStomav1 model, follow the steps below:

1. **Open the Jupyter Notebook:**
   - Navigate to the `notebooks/` directory and open the `extract_parameters.ipynb` notebook.

2. **Download the Model Weights and Test Images:**
   - Download the model weights (`model_final.pth`) and configuration file (`config.yaml`) from the following Google Drive link: [Google Drive](https://drive.google.com/drive/folders/1jYga1tsGj7DyVwska3clroRCkT_c0MZd?usp=drive_link).
   - Place the downloaded files in the `models/` directory.

3. **Install Detectron2:**
   - Run the following command to install Detectron2:
     ```sh
     python -m pip install 'git+https://github.com/facebookresearch/detectron2.git'
     ```

4. **Run the Notebook:**
   - Follow the instructions provided in the `extract_parameters.ipynb` notebook to execute the model and perform stomata detection.

## Contact
For any questions or inquiries, please contact [Sainath Reddy Gummi](mailto:gummisainath@gmail.com).
