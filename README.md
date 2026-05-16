# 🧠 PFE : Robustesse des Modèles Deep Learning face aux Attaques Adversariales

## 📄 Overview

This project analyzes three major classes of attacks on AI systems — adversarial attacks, data poisoning, and model extraction — with a practical focus on adversarial attacks such as FGSM, BIM, PGD, and C&W.

We evaluate multiple defense strategies including:

- Adversarial Training
- Defensive Distillation
- Random Noise Injection
- Adversarial Example Detection
- Hybrid defense approach

**Experiments are performed on two healthcare datasets:**

- Breast Cancer Wisconsin (WDBC) with MLP
- COVID-19 Radiography with CNN

---

## 🧬 Project Structure

PFE/<br>
│<br>
├── 📁 notebooks/<br>
│   ├── 📁 MLP/<br>
│   │   ├── baselineMLP.ipynb<br>
│   │   ├── adversarialTrainingMLP.ipynb<br>
│   │   ├── defensifDistillationMLP.ipynb<br>
│   │   ├── Random_noise_injectionMLP.ipynb<br>
│   │   ├── DetectionOfAdversarialExamplesMLP.ipynb<br>
│   │   └── HybridationMLP.ipynb<br>
│   │<br>
│   └── 📁 CNN/<br>
│       ├── baselineCNN.ipynb<br>
│       ├── mixing_adversarial_training.ipynb<br>
│       ├── distillation_defensif.ipynb<br>
│       ├── random_noise_injection.ipynb<br>
│       ├── detection_of_adversarial_training.ipynb<br>
│       ├── hybridation1_CNN_(resultat1).ipynb<br>
│       └── hybridation1_CNN_(resultat2).ipynb<br>
│<br>
├── 📁 data/                    # Not included due to size limits<br>
│   └── README.md<br>
│<br>
├── 📁 report/<br>
│   └── PFE_Report.pdf<br>
│<br>
└── README.md
---

## ⚙️ Installation

All required dependencies are already installed inside the notebooks.  
No additional installation steps are needed.

---

## 🚀 How to Run

You can run the notebooks in any Python environment.  
They were originally executed in Google Colab, but they also work locally.

---

## 🗂️ Datasets

- **Breast Cancer Wisconsin (WDBC)** : MLP experiments
- **COVID-19 Radiography Database** : CNN experiments

📌 See `data/README.md` for download links.

---

## 👤 Author

**Oumaima ELBAHLOULI**

[LinkedIn](https://linkedin.com/in/oumaima-elbahlouli) | [GitHub](https://github.com/OumaimaELBAHLOULI)
