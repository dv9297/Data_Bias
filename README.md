# Data_Bias

Analysis on labeled_and_scored_comments:
In order to process and analyze the scores given to the comments I observed the 50 largest and smallest score from labeled_and_scored_comments. I also observed some standard basic stats from the overall column 'score'. I wanted to look at the extremes in case they were any outliers within the extremes. I realized that while I was doing this that there was not a tally('Total_Score') on the rate/type of toxicty. Since the tally chas a direct affect on the socre I decided to create a new column that calculated the tally per row. I wanted to see if the higher the tally the higher the score and vice versa. When I performed this on the wikipedia comments, I noticed that the majority of row with higher tallies had higher score but there were some outlier in rows with the highest columns that showed that a row with a tally count of 2 can also have a score of 0.63 which is pretty hight when the mean of the score column was 0.24. The same applied to the rows with the smallest score who had a tally of 0 yet had a score 0.64. I also performed several tests on the spcific tally score and obtained basis stats to see the extremes of that score, and there were several uncorrelated scores, seperating into groups in my code allowed me to see the errors a lot better. For every tally amount I got the top 10 smallest and largest rows. There were wrongfuly categorized comments who deserved higher score in tallys with lower amounts, and scores with higher tallyes deserved lower scores of toxicity. All that to say that the toxicity function was not alwasy right and very prone to errors.
Biases:
Some of the biases that I think exist are that the system can determines the score based on words associated with a negative conotation. The system may not comprohend context and therefore give the comment a hight score of toxicity when it was not, despite the tally rates of the comments being 0. For example 'Dear god this site is horrible' was rated 0.45, when in reality this does not deserve that high of a score and the tally rate being 0. Then again there were some tally scores that was 1/6 and had a score of 0.98 and definetly was categorized correctly. I am not sure if the tally score really matter or if each type of toxic rate has a certain weight to it. There is also a possible bias of the function not being able to process certain words because people use special characters to write hateful comments. 

Personal Analysis:
Problem: 
Hypothesis
Methods
Results
What is my theory of why this happened?
