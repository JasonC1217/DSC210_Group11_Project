# DSC210_Group11_Project
Final Projectfor DSC210, Group 11:

Above all, we find that although Eigenvalue method can provide analytical solutions for linear systems and effective for computing, it is still limited to more complicated nonlinear systems without known analytical solutions. When ample datas are available, Recurrent Neural Network(RNN) method can perform well, especially for nonlinear ODEs systems and some systems where data-driven modeling is crucial, making it suitable for prediction. However, this method relies heavily on the quality and quantity of available data and requires careful tuning,  lacking clear interpretability compared with Eigenvalue method.
This project covered the problem of ODEs solving applied in biological system .
Conclusions:
We implemented Eigenvalue method as a way to solve this problem supposing the relationship between to species is independent. and then implement Recurrent Neural Network(RNN) method to solve it assuming they have a mutual influence.
In the project, we used the dataset of Lotka-Volterra predator-prey model.
We used libraries such as scikit-learn, numpy, and pandas and ran our code on colab.
Finally, we saw the limitations of the Eigenvalue method implementation, and explored a better solution which uses Recurrent Neural Network(RNN) method.
