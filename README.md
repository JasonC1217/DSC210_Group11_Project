# DSC210_Group11_Project
## Final Project for DSC210, Group 11:

# How to Solve System of ODEs

## Authors

- Jason Chen
- Can Chen
- Zihe Liu

## Description

In this project we aim to discover and compare methods to solve systems of ordinary differential equations (ODEs). We have implemented

## Environment

In order to properly run the project code, the following libraries need to be installed under a Python3 environment:

- NumPy
- Pandas
- SciPy
- Matplotlib
- Torch
- Scikit-learn

## Usage

Here's how to get started with the project:

1. Clone the repository to local folder using:
   ```
   git clone https://github.com/JasonC1217/DSC210_Group11_Project.git
   ```
2. Open the folder ```DSC210_Group11_Project```, go to the subfolder ```Project_code```.

3. Open the notebook ```Project_Notebook.ipynb```, run all the cells.

## Experiment Results

Above all, we find that although Eigenvalue method can provide analytical solutions for linear systems and effective for computing, it is still limited to more complicated nonlinear systems without known analytical solutions. When ample datas are available, Recurrent Neural Network(RNN) method can perform well, especially for nonlinear ODEs systems and some systems where data-driven modeling is crucial, making it suitable for prediction. However, this method relies heavily on the quality and quantity of available data and requires careful tuning,  lacking clear interpretability compared with Eigenvalue method.
This project covered the problem of ODEs solving applied in biological system .

Generated population dynamics when there are no interactions between species:
![plot](/Project_code/Generated_data_no_relationship.jpeg)

Predicted population dynamics using eigenvalue method:
![plot](/Project_code/Linear_model_No_Relationship.jpeg)

Generated population dynamics when there are inter-species interactions:
![plot](/Project_code/Generated_data.jpeg)

RNN learning curve:
![plot](/Project_code/Learning_Curve.jpeg)

Predicted population dynamics by RNN in comparison with the actual population dynamics:
![plot](/Project_code/RNN_Simulation_Results.jpeg)

## Conclusions:
We implemented Eigenvalue method as a way to solve this problem supposing the relationship between to species is independent. and then implement Recurrent Neural Network(RNN) method to solve it assuming they have a mutual influence.
In the project, we used the dataset of Lotka-Volterra predator-prey model.
We used libraries such as scikit-learn, numpy, and pandas and ran our code on colab.
Finally, we saw the limitations of the Eigenvalue method implementation, and explored a better solution which uses Recurrent Neural Network(RNN) method.
