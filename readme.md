# Political Bias Analysis

Lakshmipathi Balaji, Akshit Kumar *it\'s pronounced gif*

## Datasets
```
1. Dataset of LTRC from the paper - https://aclanthology.org/people/rrama-rohit-reddy-gangula/
2. We also built a dataset using Parliment debates from 1952 to 2017
```

## Methods/features followed

```
Multinomial Naive bayes - sklearn
Bernoulli Naive bayes - sklearn
Morpholgy considered 
Morphology not considered
A Neural network based method for WordtoVec
tfidf vectoriser
A RNN based model using keras
```

## Sggestions for Evaluation

```
We have made models using various combinations of above dataset and in case 
of morphology we replaced every word with it's root word.

You can observe the features used at the on the title of the file.

Confusion matrives or classification reports are given for every model in their respective files.

 This experimenting gave us some observations which are mentioned below.
```
## Observations
```
Multinomial naive bayes showed a lower accuracy than Binomial as it has many classes.

Neural Network based wordtovec model perfomed a bit better than tfidf when epochs are increased even with smaller dataset.

```

## Possible Improvaisations
```
Morphology should be handled in a much clever way to get good conclusion on political bias.

A improvised model can be made on training it with larger datasets
```