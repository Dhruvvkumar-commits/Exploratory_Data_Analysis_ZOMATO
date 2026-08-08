# Requirements

This project requires Python and the following libraries.

## Python

-   Python 3.x

## Python Libraries

-   pandas
-   numpy
-   matplotlib
-   seaborn
-   jupyter

## Install Dependencies

Run the following command in the terminal or Anaconda Prompt:

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

Or install them individually:

``` bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install jupyter
```

## Dataset Requirement

The notebook reads the dataset using:

``` python
pd.read_csv("zomato_.csv", encoding="latin-1")
```

Therefore, the file **`zomato_.csv`** must be available in the same
working directory as the notebook.

## Run the Notebook

Start Jupyter Notebook with:

``` bash
jupyter notebook
```

Then open:

``` text
Zomato EDA _Analysis(1).ipynb
```

and run the cells sequentially.

## Main Libraries and Their Purpose

  Library      Purpose
  ------------ ---------------------------------------------------
  Pandas       Data loading, cleaning, manipulation and analysis
  NumPy        Numerical operations
  Matplotlib   Data visualization
  Seaborn      Statistical visualization
  Jupyter      Running and documenting the notebook

## Compatibility Note

The notebook uses:

``` python
plt.style.use('seaborn-v0_8')
```

If this style is unavailable in an older Matplotlib installation, update
Matplotlib:

``` bash
pip install --upgrade matplotlib
```
