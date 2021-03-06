# kaggle-titanic

## The Challenge
The sinking of the Titanic is one of the most infamous shipwrecks in history.
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

## Objective
In this challenge, we ask that I build a predictive model that answers the question: "what kind of person is most likely to survive?" using passenger data (ie name, age, sex, socioeconomic class, etc.).

## What Data Will I Use in This Competition?

In this competition, I will use two similar data sets that include passenger information, such as name, age, gender, socioeconomic class, etc. One dataset is titled `train.csv` and the other is titled` test.csv`.
Train.csv will contain the details of a subset of the passengers on board (891 to be more exact) and, more importantly, will reveal whether they survived or not, also known as the "basic truth".
The `test.csv` dataset contains similar information, but does not reveal a“ basic truth ”for each passenger.
Using the patterns you find in the train.csv data, predict whether the other 418 passengers on board (found in test.csv) survived.

## Project Motivation
First project developed on the Udacity platform in the Data Scientist Nanodegree program, and also the first challenge proposed on the Kaggle platform.

## Libraries required
pandas (data manipulation and analysis), scikit-learn (machine learning library), seaborn and matplotlib (data visualization)

## Summary of Results
- accuracy of 87%
- f1-score of 80% in survivors and 90% in non-survivors

