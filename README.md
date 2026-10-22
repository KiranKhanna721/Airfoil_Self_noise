# Airfoil Self-Noise Prediction

A machine learning notebook that predicts the self-noise of an airfoil, as scaled sound pressure level in dB, from its physical and flow properties.

## Dataset

`airfoil_self_noise.dat` is the NASA Airfoil Self-Noise dataset from the UCI Machine Learning Repository. It has these features:

- Frequency (Hz)
- Angle of attack (degrees)
- Chord length (m)
- Free-stream velocity (m/s)
- Suction-side displacement thickness (m)
- **Target:** scaled sound pressure level (dB)

## What the notebook does

`Kiran_Airfoil_Self_noise.ipynb`:

1. Loads and cleans the data
2. Explores the features
3. Trains and compares regression models: Linear Regression, Decision Tree Regressor and Random Forest Regressor

## Getting started

```bash
pip install numpy pandas scikit-learn matplotlib jupyter
jupyter notebook Kiran_Airfoil_Self_noise.ipynb
```
