# Credit-Card-Fraud-Detection
Credit Card Fraud Detection - Dealing with Imbalanced Datasets
<div id="top"></div>

<br />

<p>Error: The neural net predictions function is using shallow_nn everytime instead of the model passed in, sorry about that! This changes the results a bit, but the main point is choosing and creating a model, which this doesn't impact.</p>

<br />
  
<p> The Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud </p> 

## Models Summary


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a>Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

About Dataset

It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Python](https://www.python.org/)

<p align="right">(<a href="#top">back to top</a>)</p>

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Tensorflow
  ```sh
  pip install tensorflow
  ```
* scikit-learn
  ```
  pip install -U scikit-learn
  ```
  In order to check your installation you can use
  ```
  python -m pip show scikit-learn  # to see which version and where scikit-learn is installed
  python -m pip freeze  # to see all packages installed in the active virtualenv
  python -c "import sklearn; sklearn.show_versions()
  ```
* Pandas & Numpy
  ```
  pip install pandas
  pip install numpy
  ```
* Kaggle
  ```
  pip install kaggle
  ```

### Installation

1. Create new API Token from your [Kaggle Account](https://www.kaggle.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/dogukanuykun/Credit-Card-Fraud-Detection.git
   ```
3. Download the [Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
4. Copy your API in the same folder as your .ipynb notebook

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/...`)
3. Commit your Changes (`git commit -m 'Add some ...'`)
4. Push to the Branch (`git push origin feature/...`)
5. Open a Pull Request


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Mail: uykundogukan@gmail.com

Project Link: [Link](https://github.com/dogukanuykun/Credit-Card-Fraud-Detection)

<p align="right">(<a href="#top">back to top</a>)</p>
