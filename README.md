# "Feed the Machine - Language Analysis" (Project 3)

![image.PNG](images/image.png?raw=true "Feed the Machine - Language Analysis")

Jenni Davis, David Jimenez, Elizabeth Conway, Austin Olea, Susan Farago, & Catherine Poirier (June 2021)

[For more information and detailed results, please refer to the Project Final Report!](https://github.com/svfarago/Project_3/blob/main/Project3_Feed_The_Machine_June2021.pdf)

[Final Web Page](https://github.com/svfarago/Project_3/blob/main/template/index.html)

## Problem to Solve
Can we use machine learning to accurately and effectively evaluate a trainer’s responses to essay-style questions in order to predict a trainer’s training and facilitation skills?

## Results / Findings
Based on the dataset we used, we were unable to reliably predict a trainer’s training and facilitation skills based on evaluating the trainer’s response to essay-style questions. The data was run against three different machine learning models: Scikit-Learn, Linear Regression, and Random Forest Regressor.
Next steps: Reevaluate questions in order to gain better responses. Rerun models and analyze results. It's not the model, it's the data.

### Database Information
- File #1
- Extracted from SalesForce & cleaned utilizing Tableau.
- Essay responses from 2,388 trainers to twenty open-ending questions from June 2020 - May 2021, resulting in 42,998 rows of data.

- File #2
- Extracted from SalesForce & cleaned utilizing Tableau.
- Student scoring on the respective trainer’s training and facilitation skills.
- 912 trainers taught courses of those 486 received scoring.
- Final cleaned data included 312 trainers and 6,240 records.


### Tools Used
- Tableau
- Python Pandas
- Python NLTK
- Vader Sentiment Analysis
- Matplotlib
- Machine Learning Models:
- Scikit-learn
- Naive Bayes Classifier
- GaussianNB
- Linear Regression
- Random Forest Regressor
- HTML / CSS / Bootstrap
- GitHub Pages


