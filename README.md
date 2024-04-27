# bostonhousepricing

# Software and Tools requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/download/mac)

Create a new environment

```
conda create -p venv python==version -y

```

Git commands to follow in VS Code 

```
To create a new environment
conda create -p venv python==version -y

To activate the environment 
conda activate venv/

To install the libraries in requirements.txt file
pip install -r requirements.txt

To connect to the git account
git config —global user.name “username”
git config —global user.email “email-Id” 

To add a file requirements.txt to git 
git add requirements.txt

To add all the files at once to git 
git add .

To check the status of git 
git status  

To create a commit with commit message 
git commit -m “commit message”

To push the code on to git 
git push origin main

```

Dataset Characteristics
```
Number of Instances: 506 

Number of Attributes: 13 numeric/categorical predictive. Median Value (attribute 14) is usually the target.

Attribute Information (in order):
CRIM  -   per capita crime rate by town
ZN    -   proportion of residential land zoned for lots over 25,000 sq.ft.
INDUS -  proportion of non-retail business acres per town
CHAS  -  Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
NOX   -   nitric oxides concentration (parts per 10 million)
RM    -   average number of rooms per dwelling
AGE   -   proportion of owner-occupied units built prior to 1940
DIS   -   weighted distances to five Boston employment centres
RAD   -  index of accessibility to radial highways
TAX   -  full-value property-tax rate per $10,000
PTRATIO - pupil-teacher ratio by town
B     -  1000(Bk - 0.63)^2 where Bk is the proportion of black people by town
LSTAT -  % lower status of the population
```