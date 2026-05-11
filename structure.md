# Garbage Classification Project Structure

```text
garbage-classification/
│
├── dataset/
│   │
│   ├── raw/
│   │   ├── battery/
│   │   ├── biological/
│   │   ├── cardboard/
│   │   ├── clothes/
│   │   ├── glass/
│   │   ├── metal/
│   │   ├── paper/
│   │   ├── plastic/
│   │   ├── shoes/
│   │   └── trash/
│   │
│   ├── train/
│   ├── valid/
│   └── test/
│
├── notebooks/
│   │
│   ├── 01_dataset_analysis.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_cnn_training.ipynb
│   ├── 04_mobilenet_training.ipynb
│   ├── 05_resnet_training.ipynb
│   ├── 06_model_evaluation.ipynb
│   └── 07_final_comparison.ipynb
│
├── saved_models/
│   │
│   ├── cnn_model.h5
│   ├── mobilenet_model.h5
│   └── resnet50_model.h5
│
├── results/
│   │
│   ├── graphs/
│   ├── confusion_matrices/
│   ├── predictions/
│   └── reports/
│
├── app/
│   │
│   ├── app.py
│   ├── templates/
│   │   └── index.html
│   │
│   └── static/
│       ├── css/
│       └── uploads/
│
├── requirements.txt
├── README.md
├── structure.md
├── .gitignore
└── main.py