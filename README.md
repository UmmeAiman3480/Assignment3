# Computer Vision Assignment 3
## PCB Defect Detection

### Student Information
- **Name:** Aiman
- **Roll Number:** 22F-3480
- **Section:** BS(EE)-8A
- **Course:** CS4059 - Introduction to Computer Vision

### Project Overview
This repository contains the complete solution for **Question 1 (PCB Defect Detection)** from Assignment 3.  
It includes:
- an end-to-end notebook pipeline (download, preprocess, train, evaluate, visualize),
- an alternative patch-based transfer-learning section for stronger performance,
- and a structured report draft.

### Repository Files
- `Aiman_22F-3480_A3.ipynb`: Final notebook for submission.
- `Aiman_22F-3480_A3_Report_Draft.md`: Report draft (convert to PDF for final submission).
- `requirements.txt`: Python dependencies.
- `A3_CV(8A).docx`: Assignment instructions (reference).

### Environment Setup
#### Requirements
- Python 3.10+ (Colab recommended)
- CUDA GPU (optional but strongly recommended)

#### Install
```bash
pip install -r requirements.txt
```

### Dataset
#### PCB Defects
- **Source:** [Kaggle PCB Defects](https://www.kaggle.com/datasets/akhatova/pcb-defects)
- **How it is handled:** notebook downloads automatically with `kagglehub`.
- **Expected local path after run:** `Q1_PCB_Defect_Detection/data/`

### Run
1. Open `Aiman_22F-3480_A3.ipynb` in Google Colab or Jupyter.
2. Enable GPU runtime.
3. Run all cells top to bottom.

### Implemented Features
- Data preprocessing and augmentation
- Train/val/test split
- Custom CNN (from scratch)
- ResNet-style model (from scratch)
- Patch-based ResNet18 transfer learning (alternative section)
- Evaluation:
  - Accuracy, Precision, Recall, F1
  - Confusion matrix
  - ROC-AUC (where applicable)
- Grad-CAM visualizations

### Submission Notes
- Keep notebook outputs before final submission.
- Convert report draft to PDF:
  - `Aiman_22F-3480_A3_Report_Draft.md` -> `Aiman_22F-3480_A3.pdf`

### Acknowledgments
- PyTorch and torchvision documentation
- Kaggle PCB dataset contributors
