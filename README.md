# Fraud Analysis Using Machine Learning

## Introduction
In 2000, Enron was one of the largest companies in the United States. By 2002, it had collapsed into bankruptcy due to widespread corporate fraud. In the resulting Federal investigation, a significant amount of typically confidential information entered into the public record, including tens of thousands of emails and detailed financial data for top executives. These data have been combined with a hand-generated list of persons of interest in the fraud case, which means individuals who were indicted, reached a settlement or plea deal with the government, or testified in exchange for prosecution immunity. These data have created a dataset of 21 features for 146 employees.

The scope of the project is the creation of an algorithm with the ability to identify Enron Employees who may have committed fraud. To achieve this goal, Exploratory Data Analysis and Machine Learning are deployed to clear the dataset from outliers, identify new parameters and classify the employees as potential Persons of Interest.


**email features**

| Variable                      | Definition                                                                    |
|:------------------------------|:------------------------------------------------------------------------------|
| ***to messages***             | Total number of emails received (person's inbox)                              |
| ***email address***           | Email address of the person                                                   |
| ***from poi to this person*** | Number of emails received by POIs                                             |
| ***from messages***           | Total number of emails sent by this person                                    |
| ***from this person to poi*** | Number of emails sent by this person to a POI.                                |
| ***shared receipt with poi*** | Number of emails addressed by someone else to a POI where this person was CC. |
