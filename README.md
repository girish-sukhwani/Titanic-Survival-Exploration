# Titanic-Survival-Exploration
Predicting survival outcomes of passengers from the 1912 Titanic Disaster

### Install

This project requires **Python 2.7**, **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Jupyter Notebook](http://ipython.org/notebook.html)
- [PySpark](https://spark.apache.org/docs/2.1.0/) (Only for the PySpark Implementation)

### Code

Actual code is provided in the `titanic_survival_exploration.ipynb` and `titanic_exploration_PySpark.ipynb` notebook files. Additional supporting code can be found in `visuals.py`.

### Run

In a terminal or command window, navigate to the top-level project directory `titanic_survival_exploration/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook titanic_survival_exploration.ipynb
```
or
```bash
ipython notebook titanic_survival_exploration.ipynb
```

Similarly for the PySpark implementation, run the following commands:

```bash
jupyter notebook titanic_exploration_PySpark.ipynb
```

or

```bash
ipython notebook titanic_exploration_PySpark.ipynb
```

This will open the Jupyter Notebook software and project file in your web browser.

### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)
