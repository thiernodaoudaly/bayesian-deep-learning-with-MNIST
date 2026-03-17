# Bayesian Deep Learning with MNIST

## Description

This project explores **Bayesian Deep Learning** applied to the classification of handwritten digits from the MNIST dataset.

Unlike standard neural networks, Bayesian approaches model **uncertainty in predictions**, making them particularly useful in high-risk or decision-critical applications.

## Objectives

* Implement a Bayesian Neural Network (BNN)
* Perform digit classification on the MNIST dataset
* Quantify prediction uncertainty
* Compare deterministic vs probabilistic deep learning approaches

## Tech Stack

* Python
* PyTorch / TensorFlow (depending on your implementation)
* NumPy
* Matplotlib

## Key Concepts

### Bayesian Neural Networks

In Bayesian Deep Learning, model parameters are treated as **probability distributions** rather than fixed values.

This allows the model to capture uncertainty.

### Uncertainty Estimation

Two types of uncertainty are typically modeled:

* **Epistemic uncertainty**: uncertainty in the model parameters
* **Aleatoric uncertainty**: inherent noise in the data

### MNIST Dataset

The model is trained on the MNIST dataset, which consists of:

* 60,000 training images
* 10,000 test images
* Grayscale images of handwritten digits (0–9)

## Results

The model is able to:

* Accurately classify handwritten digits
* Provide confidence estimates for predictions
* Highlight uncertain or ambiguous inputs

## Example

Input: image of digit "5"
Prediction: 5
Confidence: 0.92

For ambiguous digits, the model outputs lower confidence, demonstrating uncertainty awareness.

## Learning Outcomes

* Understanding Bayesian approaches in deep learning
* Implementing probabilistic models
* Interpreting uncertainty in predictions
* Applying ML in a more robust and reliable way

## Contributors

- Michel Junior DELANOUE
- Thierno Daouda LY

## License

This project is licensed under the MIT License.
