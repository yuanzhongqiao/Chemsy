# Chemsy - A Minimalistic Automatic Framework for Chemometrics and Machine Learning

![Chemsy Logo](https://github.com/tsyet12/Chemsy/blob/d46d0f8c1ab0b372b4684937d478ca6deaeba341/misc/wlogo.jpg)


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Current support for algorithms](#current-support-for-algorithms)
* [Getting Started](#getting-started)
  * [Dependencies](#dependencies)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


<!-- ABOUT THE PROJECT -->
## About The Project
This project is to make a lightweight and flexible automatic framework for chemometrics and machine learning. The main target for the methods are for spectroscopic data and industrial process data analysis. Chemsy provides a structured, customizable and minimalistic framework for automatic pre-processing search. The syntax of Chemsy also follows the widely-used sklearn library, and any algorithms/method that has the sklearn syntax will be usable in Chemsy.

## Current support for algorithms

Automatic pre-processing search with support for:
- Partial Least Squares with Cross Validation
- Savitzky–Golay filter
- Asymmetric Least Squares (AsLS) Baseline Correction
- Modified Polynomial Baseline Correction
- Improved Modified Polynomial Baseline Correction
- Zhang Fit Baseline Correction
- Linear Baseline Correction
- Second Order Baseline Correction
- Multiplicative Scatter Correction
- First Derivative
- Second Derivative
- Standard Normal Variate
- Robust Normal Variate
- Standard Scaler/ Autoscaling
- Min Max Scaler
- Any other algorithms with sklearn syntax can be used directly

To see what are the most updates algorithms available:
```python
import chemsy
from chemsy.help import see_methods

# see what preprocessing methods are available
see_methods(chemsy.prep.methods)

# see what prediction methods are available
see_methods(chemsy.predict.methods)
```
Return:
```
Preprocessing method supported:
['BaselineASLS', 'BaselineIModPoly', 'BaselineLinear', 'BaselineModpoly', 'BaselineSecondOrder', 'BaselineZhangFit', 'FirstDerivative', 'FunctionTransformer', 'KernelPCA', 'MSC', 'MaxAbsScaler', 'MinMaxScaler', 'PCA', 'PLSRegression', 'PartialLeastSquares', 'PowerTransformer', 'QuantileTransformer', 'RNV', 'RobustScaler', 'SNV', 'SavgolFilter', 'SecondDerivative', 'StandardScaler']

Prediction method supported:
['BayesianRidge', 'DecisionTreeRegressor', 'ElasticNet', 'GaussianProcessRegressor', 'GradientBoostingRegressor', 'KNeighborsRegressor', 'KernelRidge', 'Lasso', 'LinearRegression', 'MLPRegressor', 'PLSRegression', 'PartialLeastSquaresCV', 'RandomForestRegressor', 'Ridge']

```


<!-- GETTING STARTED -->
## Getting Started


## Installation

### Quick evaluation on Google Colab:
For quickstart/evaluation of the functionality, see [`this colab`](https://colab.research.google.com/drive/19_nPiAOQN9o5kxnXBjYqDvgEGhbZGD2K?usp=sharing) notebook online.

### Install on local python environment:
In a environment terminal or CMD:
```bat
pip install git+https://github.com/tsyet12/Chemsy --quiet
```


<!-- USAGE EXAMPLES -->
## Usage

To be updated.


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b testbranch/prep`)
3. Commit your Changes (`git commit -m 'Improve testbranch/prep'`)
4. Push to the Branch (`git push origin testbranch/prep`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the Open Sourced BSD-2-Clause License. See [`LICENSE`](https://github.com/tsyet12/Chemsy/blob/main/LICENSE) for more information.



<!-- CONTACT -->
## Contact

Sin Yong Teng: sinyong.teng@ru.nl or tsyet12@gmail.com


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
Martijn Dingemans martijn.dingemans@gmail.com
