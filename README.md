Here we are measuring the performance of the athletes at the Tokyo 2020 Olympics game using classification techniques like Naive Bayes, 
Decision Tree and KNN with the help of RapidMiner. The performance is measured based on medals.

Data Set Description :
1. The dataset was obtained from Kaggle community ( https://www.kaggle.com/aliaamiri/2020-summer-olympics-dataset ) which consists of data related to the game performance from Tokyo
Olympics held in 2020. There are in total 15121 rows and 12 columns. Each sample (row) has
the following characteristics (columns):
• Code
• Name
• Gender
• Age
• NOC
• Country
• Discipline
• Sport
• Event
• Rank
• Medals
2. The available ‘2020_Olympics_Dataset’ doesn’t contain any Null or missing values. Due to
greater correlation in the performances, we will be using Medals for classification purpose.
3. The classification goal is to predict the performance in the recently held Tokyo 2020 Olympics

Accuracy :

Naive Bayes 99.63
Decision Tree 83.92
KNN 85.31
