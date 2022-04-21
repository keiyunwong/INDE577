# Single Neuron
Author: Xiaoyue Li

## Introduction
This folder implements Single Neuron Logistic / Linear Regression, and evaluates the performance of each algorithm.


## Data
### Palmer Archipelago (Antarctica) penguin data

![penguins](lter_penguins.png)

Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network. [https://github.com/allisonhorst/palmerpenguins/blob/master/README.md]

Variables contained:

- species: penguin species (Chinstrap, Adélie, or Gentoo)
- bill_length_mm: bill length (mm)
- bill_depth_mm: bill depth (mm)
- flipper_length_mm: flipper length (mm)
- body_mass_g: body mass (g)
- island: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica)
- sex: penguin sex

### Wine Quality Data Set
The  dataset is related to red and white variants of the Portuguese "Vinho Verde" wine. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.). [https://archive.ics.uci.edu/ml/datasets/wine+quality]

Input variables (based on physicochemical tests):

- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol

Output variable (based on sensory data):

- quality (score between 0 and 10)

## Libraries
- Numpy [https://numpy.org/]
- Pandas [https://pandas.pydata.org/docs/]
- Sklearn [https://scikit-learn.org/stable/]
- Matplotlib [https://matplotlib.org/]
- Seaborn [https://seaborn.pydata.org/]


## Reference
- Gorman KB, Williams TD, Fraser WR (2014). Ecological sexual dimorphism and environmental variability within a community of Antarctic penguins (genus Pygoscelis). PLoS ONE 9(3):e90081. https://doi.org/10.1371/journal.pone.0090081
- Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size measurements and isotopic signatures of foraging among adult male and female Adélie penguins (Pygoscelis adeliae) nesting along the Palmer Archipelago near Palmer Station, 2007-2009 ver 5. Environmental Data Initiative. https://doi.org/10.6073/pasta/98b16d7d563f265cb52372c8ca99e60f (Accessed 2020-06-08).
- P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.
Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
