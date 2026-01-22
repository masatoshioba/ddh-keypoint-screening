# Landmark-based DDH Screening (IHDI-guided triage)

This repository contains code and environment manifests accompanying:
“Landmark-based deep learning for radiographic screening for developmental dysplasia of the hip in infants: development and external evaluation with IHDI-guided triage”.

## Contents
- `notebooks/`: example training and inference notebooks (sanitized; no patient data).
- `requirements.txt`: minimal Python dependencies.
- `environment_manifest.txt`: OS/CUDA/driver notes (optional).

## Data availability
Patient radiographs are not publicly shareable due to institutional policy.

## How to reproduce (high-level)
1. Create a Python 3.10 environment.
2. `pip install -r requirements.txt`
3. Prepare your own data in the COCO-style layout described in the paper.
4. See `notebooks/keypoint_inference_supplement.ipynb` for inference steps.

## License
MIT
