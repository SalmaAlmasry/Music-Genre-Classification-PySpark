# Music-Genre-Classification-PySpark 🎶
Have you ever wondered what makes us, humans, able to tell apart two songs of different genres? How we do we inherenly know the difference between a pop song and heavy metal? This type of classifcation may seem easy for us, but it's a very difficult challenge for a computer to do. So the question is, could an automatic genre classifcation model be possible? <br> <br>
For this project we will be **using PySpark for Classifying songs based on a number of characteristics into a set of 23 electronic genres.**
<br>
This technology could be used by an application like Pandora to recommend songs to users or just create meaningful channels. Super fun!

## Dataset
### Source: https://www.kaggle.com/caparrini/beatsdataset
beatsdataset.csv Each row is an electronic music song. The dataset contains 100 song for each genre among 23 electronic music genres, they were the top (100) songs of their genres on November 2016. The 71 columns are audio features extracted of a two random minutes sample of the file audio. These features have been extracted using pyAudioAnalysis (https://github.com/tyiannak/pyAudioAnalysis).
## Our Task
Create an algorithm that classifies songs into the 23 genres provided. Test out several different models and select the highest performing one. Also play around with feature selection methods and finally try to make a recommendation to a user.
## Steps
1) Cleaning and Preparing the data
2) Using vector Assembler to convert the columns into vectorized feature that is used as input to the model.
3) Features Selection
4) Training and Evaluating different models <br>
:point_right: 
We tried and evaluated each of the following models:
    - one vs rest
    - logistic regression
    - multi layer preceptron
    - linear SVC
    - Naive Bayes
    - GBT Classifier
    - Random Forest
    - Decision Tree
5) Implementing the best model (Random Forest)
6) Evaluating on the test set

