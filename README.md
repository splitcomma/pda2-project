# Project II - Programming for Data Analysis

This project investigates **the Wisconsin Breast Cancer** dataset. 

## Requirements of the project:

- Undertake an analysis/review of the dataset and present an overview and background.
- Provide a literature review on classifiers which have been applied to the dataset and
compare their performance
- Present a statistical analysis of the dataset
- Using a range of machine learning algorithms, train a set of classifiers on the dataset (using
SKLearn etc.) and present classification performance results. Detail your rationale for the
parameter selections you made while training the classifiers.
- Compare, contrast and critique your results with reference to the literature
- Discuss and investigate how the dataset could be extended – using data synthesis of new
tumour datapoints

## Project file structure:
```
.
├── README.md
├── data.csv
├── images
│   └── pict1.PNG
└── project_2.ipynb
```

## How to run Jupyter notebook

### Installation requirements:
- [Python](https://www.pypa.io/en/latest/)
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html#windows-installers)

Run this command to make sure Python and Miniconda is installed:
```
python --version
```

```
conda --version
```

Install a few key packages. In the Anaconda Prompt, type:
```
conda install jupyter
```
When prompted with ‘Proceed ([y]/n)?’ type y

Once the installation completes, in the Anaconda Prompt, type:
```
jupyter notebook
```
A Jupyter Notebook interface will appear in your default browser.

Open a new Anaconda Prompt and copy and paste the following commands (hit ‘Enter’ after each row):

```
pip install pandas
pip install scikit-learn
pip install matplotlib
pip install seaborn
pip install numpy
pip install -U imbalanced-learn
```

In case if jupyter notebook doesn't run on Windows laptop, please check this [solution](https://stackoverflow.com/questions/41034866/running-jupyter-via-command-line-on-windows)
Run:
```
python -m notebook
```

### References used for README:

- Further references for installing and setup Jupyter at this [link](https://www.codecademy.com/article/setting-up-jupyter-notebook)
- Used reference for formatting README at this [link](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- What should include in README [link](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)
