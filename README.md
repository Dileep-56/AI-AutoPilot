# AI AutoPilot

AI Autopilot is an innovative deep learning project that utilizes computer vision techniques to predict accurate steering angles for autonomous vehicles. This repository contains the codebase and model architecture that enables an AI system to autonomously steer a car by analyzing input images captured from a front-facing camera.
### Demo:
<img width="491" alt="Screenshot 2023-07-24 225732" src="https://github.com/Dileep-56/AI-AutoPilot/assets/121457201/ee928ecc-db27-402e-b3e3-42d8e245073b">
<img width="436" alt="Screenshot 2023-07-24 225901" src="https://github.com/Dileep-56/AI-AutoPilot/assets/121457201/74853d34-4df4-4039-99df-bf2275fe5d2f">

## Installation

- Clone the repository:

```bash
  git clone https://github.com/Dileep-56/AI-AutoPilot.git

```
- Install the required dependencies:
```bash
  pip install -r requirements.txt
```
- Download the dataset [here](https://www.kaggle.com/datasets/roydatascience/training-car/download?datasetVersionNumber=1) and place it in the data directory.
- Run `model_training.py` file in src/components/model_training.py
- Then specify the path of the images and path of the saved model in `evaluate_model.py` file in src/components/evaluate_model.py
