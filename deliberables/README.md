## Abstract

**Title**: Exploring the Effect of the Characteristics of Convicts in Norfolk Island Penal Colony on Their Sentence Length

**Keywords**: Association Mining, Clustering, Regression, Neural Network

**Type**: Individual Project

**Duration**: April 2025 – May 2025

**Course Name**: [COMP8410](https://programsandcourses.anu.edu.au/2025/course/comp8410) – Data Mining

**Course Outline**: Students in this course were assigned the Norfolk Island Penal Colony dataset. Following that, students were required to independently develop their own research questions and conduct the research using at least three distinct data mining techniques.

**Course Final Mark**: 78 / 100

**Project Weight**: [29%](https://programsandcourses.anu.edu.au/2025/course/COMP8410/First%20Semester/3820) of COMP8610

**Project Mark**: 83 / 100

**Deliverables**: [report](https://github.com/glowing-sea/norfolk-island/blob/main/deliberables/report.pdf), [code](https://github.com/glowing-sea/norfolk-island)

**Description**:

- This project explores the demographic record of convicts at the Norfolk Island Penal Colony, specifically the relationship between convict characteristics and sentence length.
- It is significant for historians to recover missing data on sentence length and for legal researchers to evaluate the fairness and justice of the law at the time.
- The project utilises Apriori association mining for feature selection, k-prototypes for outlier detection and removal, and multi-layer perceptron neural networks for training and prediction.
- The project has built two neural network models: one predicts whether a convict is sentenced to a fixed-term or lifetime sentence with an accuracy of 0.757 and an F1 of 0.691, and the other predicts the actual sentence length for all fixed-term convicts with a MAE of 2.75 years.
- The results show that criminal record, religion, and literacy are major factors related to convicts’ sentence lengths.
- Future work involves leveraging Large Language Models for Text Mining to further improve model predictions, as some columns, such as “note”, contain valuable features but are excluded during data preprocessing due to their unstructured nature.