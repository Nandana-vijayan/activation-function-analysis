# EXPLORING THE ROLE OF ACTIVATION FUNCTIONS IN NEURAL NETWORK TRAINING AND PERFORMANCE
This project compares various activation functions (ReLU, Sigmoid, Tanh, Leaky ReLU) in deep learning models, analyzing their impact on training dynamics such as loss and accuracy. It includes code for experiments, visualizations of results, and a tutorial to guide users in modifying and running their own analyses.

# Files and Structure

• **Activation_Functions_NN_Performance_CIFAR-10_Tutorial.ipynb:** This Jupyter Notebook contains the code used for the analysis. It includes the implementation of various neural network models using different activation functions (ReLU, Sigmoid, Tanh, and Leaky ReLU) and plots the corresponding training accuracy and loss for comparison.

• **Activation-Functions-Tutorial.pdf:** A detailed tutorial explaining how the code works, step-by-step instructions on using the repository, and best practices when experimenting with activation functions.

• **plots/:** Directory containing the saved figures for accuracy and loss plots generated during the analysis. These images include colorblind-friendly palettes and alt-text for better accessibility.


# Key Features

• **Comparison of activation functions:** Compares how different activation functions influence model accuracy and loss across epochs.

• **Colorblind-friendly visualizations:** Uses distinguishable color palettes to ensure that the plots are readable for users with colorblindness.

• **Alt-text for images:** Includes descriptive alt-text for images, ensuring better accessibility for users with visual impairments.

# Requirements
To run the analysis and generate results from the code, the following dependencies are required:

• PyTorch

• Matplotlib

• NumPy

• Python >= 3.7

You can install the necessary dependencies by running the following command in your terminal or command prompt:
pip install torch torchvision matplotlib numpy

# How to Run
**1. Clone the Repository**
Start by cloning this repository to your local machine using the command:

git clone https://github.com/Nandana-vijayan/activation-function-analysis.git

**2. Install Dependencies**
If you don't already have them, install the required libraries:

pip install -r requirements.txt

**3. Run the Jupyter Notebook**

• Open Activation_Functions_NN_Performance_CIFAR-10_Tutorial.ipynb in Jupyter Notebook, and run the cells sequentially.

• The notebook will train neural network models with different activation functions and generate plots that compare their performance (training loss and accuracy).

**4. View the Results**

• Access the plots/ directory to find saved plots of training loss and accuracy, created using colorblind-friendly palettes and properly annotated with alt-text.

# Plot Examples

**Training Loss Across Epochs**

The loss plots show how the training loss evolves across epochs for models using different activation functions. In particular, it demonstrates how ReLU generally converges faster compared to others like Sigmoid and Tanh.

**Test Accuracy for Different Activation Functions**

The bar chart illustrates how models with different activation functions perform in terms of test accuracy after training.

# Sample Plot Output

• **Loss Plot:** Shows training loss for each activation function over the epochs.

• **Accuracy Plot:** Displays bar plots for comparison of accuracy across models with different activation functions.

# Tutorial

The tutorial PDF is included in the /tutorials folder. It explains:

• **Theory** of each activation function.

• **Model setup** and experiment details.

• **Results:** Analysis of accuracy and training loss comparisons for each function.

**To view the tutorial:**

Open tutorials/Activation-Functions-Tutorial.pdf.

# Contributing
Contributions are welcome! If you want to suggest improvements or add new features, feel free to fork this repository and create a pull request. Please make sure that your contributions align with the accessibility standards and coding style of the repository.

# License

This project is licensed under the MIT License. You can freely use, modify, and distribute the project.

For more details, see the LICENSE file.
