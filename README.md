# PFE
📄 Overview:

This project analyzes three major classes of attacks on AI systems — adversarial attacks, data poisoning, and model extraction — with a practical focus on adversarial attacks such as FGSM, BIM, PGD, and C&W.
We evaluate multiple defense strategies including Adversarial Training, Defensive Distillation, Random Noise Injection, Adversarial Example Detection, and a hybrid defense approach.
Experiments are performed on two healthcare datasets:

 Breast Cancer Wisconsin (WDBC) with MLP
 COVID-19 Radiography with CNN

🧬 Project Structure:

PFE/

│

├── 📁 notebooks/

│   ├── 📁 MLP/

│       ├── DetectionOfAdversarialExamplesMLP.ipynb
        
│        ├── HybridationMLP.ipynb
        
│        ├── Random_noise_injectionMLP.ipynb
        
│        ├── adversarialTrainingMLP.ipynb
        
│        ├── baselineMLP.ipynb
        
│        └── defensifDistillationMLP.ipynb      
     
│   ├── 📁 CNN/

│        ├── baselineCNN.ipynb
        
│        ├── detection of adversarial training.ipynb
        
│        ├── distillation defensif.ipynb
        
│        ├── hybridation1_CNN_(resultat1).ipynb
        
│        ├── hybridation1_CNN_(resultat2).ipynb
        
│        ├── mixing_adversarial_training.ipynb
        
│        └── random_noise_injection.ipynb

│

├── 📁 data/              # (Not included due to size limits)

│   └── README

│

├── 📁 report/

│   └── PFE_Report.pdf

│

└── README.md

⚙️ Installation:

All required dependencies are already installed directly inside the notebooks.  
No additional installation steps are needed.

🚀 How to Run:

You can run the notebooks in any Python environment.  
They were originally executed in Google Colab, but they also work locally.

🗂️ Datasets:

Breast Cancer Wisconsin (WDBC)
COVID-19 Radiography

👤 Author:

ELBAHLOULI Oumaima – Master Data Science and Bioinformatics
