# LightGBM Plugin

The LightGBM plugin provides option in Dataiku DSS to use this algorithm with DSS Visual Machine Learning.

>LightGBM is a gradient boosting framework that uses tree based learning algorithms. It is designed to be distributed and efficient with the following advantages: <br>* Faster training speed and higher efficiency.<br>* Lower memory usage.<br>* Better accuracy.<br>* Support of parallel and GPU learning.<br>* Capable of handling large-scale data

[Microsoft's LightGBM documentation](https://github.com/microsoft/LightGBM)


## Installation

This plugin does not provide a code environment. You need to run your model training within a code environment where the package lightGBM and jinja2 are installed.

If you want to use other algorithms along side with lightGBM in the Visual Machine section, we recommend you to also install scipy, scikit-learn and xgboost packages (*Administration -> Code envs -> Choose your code env -> Packages to install -> Add sets of packages -> Visual Machine Learning*).


## Usage
* In your visual ML task, go to Advanced -> Runtime environment -> Choose the appropriate code environment.
* Select the LightGBM custom algorithm in your visual machine learning tasks.

Please see [plugin page](https://www.dataiku.com/dss/plugins/info/lightgbm.html) on Dataiku's website for further details of the algorithm.

You can also ask your questions on our Q&A, [answers.dataiku.com](https://answers.dataiku.com), or open an [Github issue](https://github.com/dataiku/dataiku-contrib/issues).

# License

The LightGBM plugin is:

   Copyright (c) 2019 Dataiku SAS
   Licensed under the [MIT License](LICENSE.md).
