# BRATS
Brain Tumor Segmentation Using U-Net

Project Overview

Key Objectives:
The goal of this project is to develop a deep learning model that can accurately segment brain tumors from MRI images using the U-Net architecture. This model can assist medical professionals in diagnosing and analyzing brain tumors more efficiently, reducing the manual effort required to process and identify tumors in medical scans.

Results and Insights:
Achieved Performance Metrics:
Dice Coefficient: 0.9934 (average), indicating high overlap between predicted and ground truth tumor areas.
Accuracy: 98.84% (training), 98.68% (validation), demonstrating excellent model performance.
Loss: The model consistently shows low loss, with the training loss at 0.0332 and validation loss at 0.0407, indicating that the model is learning effectively.
The model was trained using MRI image data and i used T1 slice images, with segmentation of brain tumors as the primary task. The use of U-Net, a proven architecture for image segmentation, ensures that the model can precisely segment tumor regions even with relatively few training samples.
Motivation:
The motivation behind this work is to leverage deep learning for medical image segmentation tasks, which is crucial for automating and accelerating medical diagnoses. The ability to accurately segment tumors from MRI scans will help clinicians make quicker and more accurate decisions, ultimately improving patient outcomes.
Memory usage :
<img width="242" alt="Screenshot 2024-11-29 at 9 37 34 pm" src="https://github.com/user-attachments/assets/ab7c32c2-1010-4478-8960-aeb5a84c447e">


Training the Model:
<img width="869" alt="Screenshot 2024-11-29 at 9 51 53 pm" src="https://github.com/user-attachments/assets/b766803c-9d0f-48d7-a195-86428287860a">


Training and Validation accuracy :<img width="592" alt="Screenshot 2024-11-29 at 9 52 39 pm" src="https://github.com/user-attachments/assets/01abeba7-747b-418b-9097-e322133e90bd">

Training and Validation losses:<img width="573" alt="Screenshot 2024-11-29 at 9 52 06 pm" src="https://github.com/user-attachments/assets/c27bf5db-b22e-4528-a748-5e270b772dc0">


Dice loss : 
<img width="382" alt="Screenshot 2024-11-29 at 9 52 49 pm" src="https://github.com/user-attachments/assets/7ed98808-aefd-47c2-afec-13b4eb9bcad8">



