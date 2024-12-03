# Applied-Statistics

Author: Francesco Troja

This repository serves as a key resource for the project and task assignments of the **HDip in Computing within ATU University's Data Analytics program**, specifically for the **Applied Statistics** module. It contains two *Jupyter notebooks*: `tasks.ipynb`, which focuses on detailed task analyses, and `project.ipynb`, dedicated to in-depth project exploration.

## *Task Problem Statement*

Throughout the course, four distinct tasks were selected and executed, each addressing specific aspects and challenges:

- **Task 1**: This task explored a *variation* of the **Lady Tasting Tea** experiment, where we had *12 cups* in total. The challenge was to *calculate the probability* of correctly selecting the cups with milk first, under the assumption that no special abilities were involved in the selection process.
- **Task 2**: This task focused on evaluating the functionality of `numpy.random.normal()` for generating values that follow a **normal distribution**. Then the next step was to test the sample's conformity to a normal distribution by applying the **Shapiro-Wilk Test**.
- **Task 3**: This task involved performing a **$t$-test** to *compare the resting heart rates* of patients **before** and **after** a two-week exercise program. The goal was to calculate the $t$-statistic and compare it with the value obtained using the scipy library, explaining the process and interpreting the results.
- **Task 4**: The focus of this task was on *estimating the probability* of committing a **Type II error** in the context of a **One-Way ANOVA** test.

Each task presented unique challenges and opportunities for exploration, contributing to a comprehensive understanding of various statistical concepts and methodologies.

## *Project Problem Statement*

The final project focuses on analyzing the `PlantGrowth R dataset` to explore its *structure* and derive *insights* through *statistical methods*. This involves downloading the dataset, describing its key variables (treatment groups and plant weights), and explaining the theoretical concepts of **$t$-tests** and **ANOVA**. The analysis includes performing a $t$-test to assess differences between the treatment groups `trt1` and `trt2` and conducting ANOVA to determine significant differences among `ctrl`, `trt1`, and `trt2`. Additionally, the project explains why ANOVA is preferred over multiple t-tests for comparisons involving more than two groups, emphasizing its statistical relevance and efficiency.

## How to download the Repository

Access the provided link: [Tasks](hhttps://github.com/C-3sc0/applied_statistics/blob/main/tasks.ipynb), [Project](https://github.com/C-3sc0/applied_statistics/blob/main/project.ipynb) and select the `<> Code` button. There are two options for accessing the Jupyter Notebook:

- Download it as `ZIP file`;
- clone the repository using the provided `HTTPS link` and integrate it into your local machine.

## Repository's Content

- A file named **README.md** file;
- The [`tasks.ipynb`](hhttps://github.com/C-3sc0/applied_statistics/blob/main/tasks.ipynb) file;
- The [`project.ipynb`](https://github.com/C-3sc0/applied_statistics/blob/main/project.ipynb) file;
- A [`gitignore`](https://github.com/C-3sc0/applied_statistics/blob/main/.gitignore) file;
- A [`requirement.txt`](https://github.com/C-3sc0/applied_statistics/blob/main/requirements.txt) file;
- The [`PlantGrowth.csv`](https://github.com/C-3sc0/applied_statistics/blob/main/PlantGrowth.csv) file, containing the data of the PlantGrowth Dataset;
- A folder labeled [`images`](https://github.com/C-3sc0/applied_statistics/tree/main/images) where all images used during the tasks analysis are stored.

## Technologies Used

The project utilizes **Python 3** as its primary technology stack. To execute the code within the Jupyter Notebook, it's essential to have Python 3 or a higher version installed. The official Python package can be obtained from the [Python website](https://www.python.org/downloads/) for download and installation. The utilization of Python 3 ensures compatibility with an extensive array of libraries and tools.
The libraries employed in the current notebook include:

- `Pandas`  Provides data structures and tools for data manipulation and analysis, particularly with tabular data (The documentation can be found in the following link: [Pandas](https://pandas.pydata.org/docs/));
- `Matplotlib` A comprehensive library for creating static, animated, and interactive visualizations in Python (The documentation can be found in the following link: [Matplotlib](https://matplotlib.org/stable/index.html));
- `Numpy` Offers support for large, multi-dimensional arrays and matrices, along with mathematical functions to operate on them (The documentation can be found in the following link: [Numpy](https://numpy.org/doc/stable/));
- `Seaborn` A data visualization library based on Matplotlib that provides a high-level interface for creating attractive and informative statistical graphics (The documentation can be found in the following link: [Seaborn](https://seaborn.pydata.org/));
- `math` A library for performing mathematical operations such as trigonometry, logarithms, and factorials (The documentation can be found in the following link: [math](https://docs.python.org/3/library/math.html));
- `itertools` A standard library module providing functions to create and work with iterators for efficient looping (The documentation can be found in the following link: [itertools](https://docs.python.org/3/library/itertools.html));
- `random` A module for generating pseudo-random numbers and performing random operations like sampling or shuffling (The documentation can be found in the following link: [random](https://python.readthedocs.io/en/stable/library/random.html));
- `scipy` A library for scientific and technical computing, offering modules for optimization, integration, interpolation, and more. (The documentation can be found in the following link: [scipy](https://scipy.org/));

The majority of the required libraries are typically pre-installed in the Python environment. In cases where a library is not present, the `pip command``, serving as the Python package installer, can be employed. To facilitate the installation process, open the terminal and execute the following command:

```python
pip install library_name
```

It's important to substitute "library_name" with the actual name of the library intended for installation.

## References

In the notebook, references are appropriately cited within the sections where they're utilized and compiled at the end. While some references might not be directly applied in the notebook, they were consulted to enhance comprehension of the related topics covered.