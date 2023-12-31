# Sklearn Pipeline Tutorial

## Overview
This Jupyter notebook provides a quick tutorial on using the scikit-learn library for machine learning in Python. It combines discussions on the impact of hardware, specifically processing cores, with practical machine learning applications. Key sections include:

1. **AI Generated Pipeline**: An introduction into a Chatgpt-generated scikit-learn pipeline for logistic regression. This code is an example of a basic scikit-learn pipeline but greedily utilizes all cores which can cause issues on shared systems like the Yens.
2. **Why Cores Matter**: This section shows the significance of processing cores in machine learning, providing insights into computational efficiency and performance.  A quick comparative study on the performance and implications of using 10 and 40 processing cores.
3. **Predictions**: This section shows one way you might perform inference with pre-trained pipelines
4. **Scoring**: A quick look into one way to evaluate these machine learning pipeline outputs

## Prerequisites
To get the most out of this tutorial, you should have:
- Basic knowledge of Python programming.
- An understanding of fundamental machine learning concepts.
- Python 3.x installed on your machine.
- Jupyter Notebook or Jupyter Lab installed.

## Installation
Before starting, ensure you have the following Python libraries installed:
- `scikit-learn`: for machine learning algorithms and tools.
- `numpy`: for numerical computations.
- `pandas`: for data manipulation and analysis.

You can install these packages using pip:
```bash
pip install scikit-learn numpy pandas
```

## Running the Notebook
1. Clone or download this repository to your local machine or the [Yens](https://rcpedia.stanford.edu/yen/webBasedCompute.html).
2. Navigate to the directory containing the notebook.
3. Open the `Sklearn_Pipeline.ipynb` file in the Jupyter interface.
4. Execute the cells in order to follow along with the tutorial.

## Contributing
Contributions to this tutorial are welcome! If you have suggestions or improvements, feel free to submit a pull request or open an issue.
