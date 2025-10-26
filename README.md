# Caus-TD: Consistency-Regularized Causal Teacher–Student Learning with Diffusion Synthesis for PCOS Diagnosis

This repository provides the official implementation of **Caus-TD**, a semi-supervised learning framework that integrates causal reasoning, diffusion-based data synthesis, and consistency regularization for reliable **PCOS diagnosis** from ultrasound images.

---

## Repository Structure
```
Caus-TD/
├── ADiS/              # Diffusion synthesis
├── CaTS/              # Causal teacher–student framework
├── Post_Filtering/    # Filtering of synthetic images
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```
---

## Datasets


| DATASET | SOURCE |
|----------|---------|
| **PCOS Dataset** | [LINK](https://www.kaggle.com/datasets/anaghachoudhari/pcos-detection-using-ultrasound-images) |
| **PCOSGen Dataset** | [LINK](https://zenodo.org/records/14591782) |
| **MMOTU (2D subset)** | [LINK](https://github.com/cv516Buaa/MMOTU_DS2Net) |

---


## Quickstart

```bash
# Clone the repository
git clone https://github.com/<your_username>/Caus-TD.git
cd Caus-TD

# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate       # Linux/macOS
# or .venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
```
---
## License

This project is released under the **MIT License**.  
See the [LICENSE](./LICENSE) file for details.
