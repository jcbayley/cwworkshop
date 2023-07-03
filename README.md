# cwworkshop

Workshop on how to use the wide parameter space search tool SOAP and how machine learning is used within SOAP.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jcbayley/cwwworkshop/blob/main/cwworkshop_soap.ipynb)

## Running locally

To run the tutorial locally, first clone the repository:

```bash
git clone https://github.com/jcbayley/cwworkshop.git
```

Then install the dependencies. We suggest using a virtual environment (`venv`) or `conda` environment. This will keep the installation separate from the system installation. See below from instructions.

Once you have installed the dependencies and activated the environment, run the following command in the base directory of the repository

```bash
jupter notebook
```

and then navigate to the jupyter notebook: `cwdetection_soap.ipynb`.


### Using conda

A conda environment can be created directly from the [environment file](https://github.com/jcbayley/cwworkshop/blob/main/environment.yml) found in the git repository:

```bash
conda env create -f environment.yml
```

The environment will be called `cwsoap` and can be activated by running

```bash
conda activate cwsoap
```

### Using virtual enviroment

Follow the instructions [here](https://docs.python.org/3/tutorial/venv.html#creating-virtual-environments) to create a virtual environment and then activate the environment. Once it is activated, the dependencies can be installed using the [`requirements.txt` file](https://github.com/jcbayley/cwworkshop/blob/main/requirements.txt) found in the git repository:

```bash
pip install -r requirements.txt
```