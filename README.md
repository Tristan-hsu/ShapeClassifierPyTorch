# ShapeClassifierPyTorch

# Probability & Statistics + Basic Shape Classifier

ShapeClassifierPyTorch/
├── README.md
├── requirements.txt
├── first_two_question.ipynb
├── Shape_Classifier.ipynb
└── dataset/
    ├── circle/
    │   ├── c1.png
    │   ├── c2.png
    │   └── ...
    ├── square/
    │   ├── s1.png
    │   ├── s2.png
    │   └── ...
    └── triangle/
        ├── t1.png
        ├── t2.png
        └── ...

This repository contains two parts:

1. **Probability and Statistics Exercises**  
   Implemented in [`first_two_question.ipynb`](./first_two_question.ipynb).
   This is an notebook illustrating two questions—one on probability and one on causal reasoning—along with brief computations and explanations.


2. **Basic Shape Classifier**  
   Implemented in [`Shape_Classifier.ipynb`](./Shape_Classifier.ipynb).
    "In this notebook, we:\n",
    "1. Generate a dataset of shape images using the PIL library (e.g., circles, squares, triangles).\n",
    "2. Build a simple image classifier based on the AlexNet architecture.\n",
    "3. Train the model using SGD.\n",
    "4. Evaluate accuracy and discuss the results."

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)

---

## Prerequisites
- Python 3.8 or above (recommended)
- See [requirements.txt](./requirements.txt) for other necessary packages.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-user/your-repo-name.git
2. **Virtual environment**
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. **Install dependencies**
pip install -r requirements.txt
