# Hand Written Roman Numeral Recognition

## Introduction

This project illustrates how roman handwritten digits can be classified with machine learning using the CRISP-DM process. The goal of this project is to demonstrate what is possible in a 5-weeks long project with a more research-oriented approach.

## Project Structure

The project is structured as follows:

- [classifiers](classifiers): Contains the saved model
- [CRISP-DM-Notebooks](CRISP-DM-Notebooks): Contains the notebooks with the Python code for each step of the CRISP-DM process
- [dataset-images](dataset-images): Contains the images of the dataset used for training and testing. Since the dataset is large in size, it is not committed to the repository. For details where and how to get the dataset, see the [README](./dataset-images/README.md) in the dataset-images folder.
- [dataset-numpy](dataset-numpy): Contains the saved CSV files of the dataset used for training and testing. These files contain the extracted features from the images (both raw and cleaned). The artifact are also not committed to the repository. To generate them, run all notebooks steps in [CRISP-DM-Notebooks](CRISP-DM-Notebooks) in order.

## Getting Started

### Prerequisites

- Python 3.10 or higher
- IDE or environment to run Jupyter Notebooks
- Required Python packages (see [requirements.txt](requirements.txt))

### Installation

The following commands are for macOS. For other operating systems, the commands may differ.

1. Set up your Python environment (optional)

```
python3 -m venv .venv
```

2. Activate the virtual environment

```
source .venv/bin/activate
```

3. Install the required Python packages

```
pip install -r requirements.txt
```

### Installing the Dataset

Read the [README](./dataset-images/README.md) in the dataset-images folder to get the dataset.

### Running the Notebooks

Run the notebooks in the [CRISP-DM-Notebooks](CRISP-DM-Notebooks) folder in order (from step 1 to step 5).
