
## -- -------------------------- --
NOTE: This section is autogenerated by readme_ation, manual updates will be overwritten
### MNIST Digit Classification with Neural Networks
#### Overview
This project implements a neural network model to classify handwritten digits from the MNIST dataset. It explores various techniques to improve model performance, including hyperparameter tuning and data augmentation.
#### Motivation
To gain hands-on experience with neural network implementation, hyperparameter optimization, and strategies for improving model accuracy on a classic machine learning problem.
#### Technologies Used
Python, PyTorch, fastai, pandas, matplotlib, seaborn
#### Approach
The project follows these main steps:
1) Data preparation and exploration,
2) Implementing a simple neural network model,
3) Grid search for hyperparameter optimization,
4) Analyzing misclassified examples,
5) Attempting to improve the model by augmenting the training data with misclassified examples.
#### Challenges and Learnings
Tuning hyperparameters effectively, handling large datasets, implementing data augmentation techniques, and interpreting results to improve model performance.
#### Key Takeaways
Grid search can effectively optimize hyperparameters. Visualizing and analyzing misclassified examples provides insights into model weaknesses. However, simply augmenting training data with misclassified examples does not guarantee improved performance.
#### Acknowledgments
The project uses the fastai library and follows some concepts from the fastai course. It also uses a custom package readme_ation for adding setup details to the README.
<!-- END OF PROJECT DETAILS -->

## -- ------------------------ --
NOTE: This section is autogenerated by readme_ation, manual updates will be overwritten

### Setup and Run Instructions

This will guide you through the process of setting up a Mamba environment and running the provided Python code to see it in action. It uses the last known working versions of Python and packages used.

#### Prerequisites

Ensure you have [Mamba](https://mamba.readthedocs.io/en/latest/installation.html) installed on your system. Mamba is a fast, cross-platform package manager.

#### Steps

1. **Create a Mamba Environment**
   
   Open your terminal and execute the following commands:

   ```shell
   mamba create -n [ENVIRONMENT_NAME] python=3.9.19 -y
   mamba activate [ENVIRONMENT_NAME]
   ```

2. **Install Necessary Packages**

    ```shell
    # Install each with mamba and fall back to pip if necessary
    for pkg in PIL=10.3.0, csv=1.0, fastai, itertools=10.1.0, matplotlib=3.8.4, pandas, pkg_vers=0.0.8, readme_ation=0.1.14, seaborn; do (mamba install $pkg -y || pip install "${pkg//=/==}"); done
    ```

3. **Run the Script**

    Ensure you are in your project directory and run:

    ```shell
    python [FILE_NAME]
    ```

    Or click 'run' in your IDE of choice.

    <!-- END SETUP AND RUN INSTRUCTIONS -->