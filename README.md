**Adversarial Machine Learning: FGSM and PGD Attacks**

This repository contains the implementation of Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD) attacks on the MNIST dataset, using PyTorch. The project demonstrates how adversarial examples can be crafted to fool machine learning models.

* **Adversarial ML (FGSM and PGD attacks).ipynb**: The main Jupyter notebook that contains the implementation of FGSM and PGD attacks.

* **Dataset**: The MNIST dataset is automatically loaded using torchvision.datasets.

* **Attacks**: Implementation of FGSM and PGD attacks to demonstrate adversarial robustness.

**Overview of Attacks**

* **FGSM (Fast Gradient Sign Method):** Perturbs the input image by calculating the gradient of the loss function with respect to the input, then modifies the image slightly in the direction of the gradient.

* **PGD (Projected Gradient Descent):** A more iterative and refined method compared to FGSM, which projects the perturbed image back onto a valid range after each update.

**Results**

The notebook includes visualizations of the adversarial examples generated using both FGSM and PGD, and shows how well these attacks can fool a trained neural network model.
