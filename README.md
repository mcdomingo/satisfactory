# Satisfactory

## Data

I created the data on a [google sheet](https://docs.google.com/spreadsheets/d/1CBYtp-opbf2fAMuOdi0NZwIyfbYJwU3mOSovMenRMx8/edit?usp=sharing) and pulled it down into a csv.

## Running the notebook

I normally use [conda](https://docs.conda.io/en/latest/miniconda.html) so create [virtual env](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) and then install the necessary packages, like so

```
conda create -n satisfactory-env
source activate satisfactory-env # or whatever your the name virtual environment is
conda install jupyter notebook pandas
```

But you can also use pip.

```
pip3 install jupyter notebook pandas
```

Finally run where you downloaded the files.

```
jupyter notebook
```

## super computers.ipynb

This notebook is an of calculating the of buildings required to make X amount of super computers.
