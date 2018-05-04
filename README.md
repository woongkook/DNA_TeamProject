# DNA_TeamProject
# Santander Product Recommendation

### Synopsis
There are 13,647,309 bank records from Jan, 01, 15 to May, 30, 16 that occured in Santander bank in Spain. Independent variables are all kinds of customer's personal information like sex, age, seniority and so on.  What we had to do was that recommend the fittest product to customers based on past visit information. 

### Things that we consiered
- How to deal with NULL values
> Some variables are asymmetric like they have only one or two classes.
>  After some kind of test, we conclude that too less class values can't influence with results.
- What kind of algorithm we use?
> We tried some basic classification algorithm at first like Logistic, LDA, QDA, But, result was not that good
> We assume that complicated algorithm can control complicated rules in data.
> After some kind of test, we think that 'XGboost' is the fittest for our model
- over 13 million data!
> it was the hardest part of this project.
> For me, I used google colab.

### Final result

Best score : 0.0298268 - 255th/1787(14%)
> feature selection : sex, age, seniority, active or not, type of customers, house income, province code  and so on
