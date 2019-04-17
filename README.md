# pandas ecosystem 2019

Slides of the _pandas ecosystem 2019_ talk.

pandas is more than 10 years old now. In this time, it became almost a standard
for building data pipelines and perform data analysis in Python.
As the popularity of the project grows, it also grows the number of projects
that depend or interact with pandas.

This talk will cover this ecosystem of projects around pandas,
mainly in the prespective of scalability and performance.
Discussing for example how projects like Arrow are key for the future of pandas,
or how Dask is overcoming pandas limitations.

In a first part, the talk will focus on pandas itself, its components,
and its architecture. This will give the required context for a second part,
that will explain related projects, how they interact with pandas,
and what the whole ecosystem can offer to users.

Talk being delivered or proposed to the next conferences:

- [PyCon X](https://www.pycon.it/en/)
- [PyLondinium](https://pylondinium.org/)
- [PyData London](https://pydata.org/london2019/)

## Set up

- Install [Miniconda 3.7](https://docs.conda.io/en/latest/miniconda.html)
- Open an Anaconda/UNIX terminal
- `git clone https://github.com/datapythonista/pandas_ecosystem.git`
- `cd pandas_ecosystem`
- `conda env create`
- `source activate pandas_ecosystem` (in Windows: `conda activate pandas_ecosystem`)
- `jupyter notebook`
- Open `pandas_ecosystem.ipynb` notebook
- Click the icon with the bar plot to show as slides with [RISE](https://damianavila.github.io/RISE/)
