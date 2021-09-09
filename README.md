<h1 align = "center"> Detection of Parkinson Disease </h1>

Parkinson's disease is a progressive nervous system disorder that affects movement. Symptoms start gradually, sometimes starting with a barely noticeable tremor in just one hand. Tremors are common, but the disorder also commonly causes stiffness or slowing of movement.

Unfortunately we dont have a proper cure to this disease. Treatment will be done with the symptoms that the patient posses. Since this is a nervous system disorder symptoms are not just realted to one particular aspect.

Some of symptoms are listed below:

- Tremor
- Depression
- Constipation
- Slow movement
- Speech changes
- Writing changes
- Bladder problems
- Sleeping disorders
- Chewing problems
- Thinking difficulties
- Loss of automatic movement

Since there was no proper cure and still unknown resons for this disease. Treatment was based on the symptoms of that person. So analysing the previous data of person who have Parkinson disease will help us to discover whether our patient have Parkinson disease.

**The results obtained are estimated. But does not give conformation on the disease.**

<h2 align = "center">Pre requsites</h2>

- Knowledge on Python
- Knowledge on Databases
  - Database can be in different formats. Some examples of Databases as follows:
    1. Excel format
    2. CSV format
    3. SQL Database
- Knowledge on Python Frameworks:
  1. Numpy
  2. Pandas
  3. XG Boost
  4. Scikit Learn

<h2 align = "center">Computational Environment</h2>

You can use any one of the environments mentioned below to run this code. I have used Jupyter Notebook extesnion in vs code.

- Jupyter Notebook
- Google colab

You can also prepare it python file.

<h2 align = "center">Installing Libraries</h2>

Installing Pandas

> pip3 install pandas

Installing NumPy

> pip3 install numpy

Installing XGBoost

> pip3 install xgboost

Installing Scikit

> pip3 install -U scikit-learn

> or

> pip install -U scikit-learn

<h2 align="center">Database or Dataset</h2>

The link to the Dataset which is in CSV format is given below:

[Click here to directly access CSV file](https://raw.githubusercontent.com/chaitanyabaranwal/ParkinsonAnalysis/master/parkinsons.csv)

This Data is taken from one more **GITHUB** repository. The link to the total repoistroy is given below:

[Click here to go to the Data Repository](https://github.com/chaitanyabaranwal/ParkinsonAnalysis)

<h2 align = "center">Importing Dataset</h2>

- You can diretly paste our link which is a CSV file while reading the file into the program.

```python
      read_csv("link")
```

- You can copy the data in a file and save it in CSV format.

```python
      read_csv("filename.csv")
```

- You can make a table in SQL and insert all these values. To read such SQL table we have a command as follows.

```python
      read_sql(connection to database)
```

<h2 align="center">XBG Classifier</h2>

XGBoost is an implementation of gradient boosted decision trees designed for speed and performance that is dominative competitive machine learning.

XGBoost provides a wrapper class to allow models to be treated like classifiers or regressors in the scikit-learn framework.

This means we can use the full scikit-learn library with XGBoost models.

The XGBoost model for classification is called XGBClassifier. We can create and and fit it to our training dataset. Models are fit using the scikit-learn API and the model.fit() function.

Parameters for training the model can be passed to the model in the constructor.

As we have many symptoms which will be passing as data which returns a single class whether the person have Parkinson disease.

<h2 align = "center">Credits</h2>

The dataset was created by **Max Little of the University of Oxford**, in collaboration with the National Centre for Voice and Speech, Denver, Colorado, who recorded the speech signals.

For more info about the database, go to:

[Click here to know more about database](https://archive.ics.uci.edu/ml/datasets/parkinsons)
