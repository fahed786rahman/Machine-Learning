# Machine-Learning
This module was an introduction to me to machine learning. Here, I learned about many machine learning techniques and will introduce the 3 projects that I completed.

Project 1:
Predicting the Olympic Games
The Olympic Games have always mixed pure sporting spectacle with national competition. During the Cold War the USA and the Soviet Union competed fiercely to win the most medals in each games. On a somewhat milder level, in Britain we often compare our medal count with that of Australia, one of our traditional sporting rivals. If you were in the UK during the summers of 2012 and 2016 you cannot have missed the excitement caused by the UK’s success relative to previous years. 

This competition is usually expressed in terms of the number of medals won by each country’s athletes ((Figure 1 top panel). However, many interested watchers, especially those from smaller countries, have pointed out that the medal table is hardly a fair reflection of a country’s sporting prowess. Some countries have a strong tradition of sporting excellence, but are simply too small to make an impact in terms of total medals. These commentators would rather look at the per capita medal count (Figure 1 bottom panel).

Looking at the per capita map above though, we see that large areas of the world are still very underrepresented. Specifically, poorer countries do not win many medals per head of population. There are many reasons for this, including a lack of investment in sport and facilities, and fewer individuals who are wealthy enough to devote their life to training. As such, it has been suggested that we should compensate for wealth when measuring a country’s Olympic performance. In this practical you will investigate how the number of medals a country wins can be predicted from national population and GDP, and how consistent these relationships are.

Project 2:
Brexit
On June 23rd, 2016, The UK had a national referendum to decide whether the country should leave the EU (‘Brexit’). The result, a win for the Leave campaign, surprised many political commentators, who had expected that people would vote to Remain. Immediately people began to look for patterns that coud explain the Leave vote: cities had generally voted to Remain, while small towns had voted to Leave. England and Wales voted to Leave, while Northern Ireland and especially Scotland voted to Remain.

In the next few days, the Guardian newspaper presented some apparent demographic trends in the vote, based on the ages, incomes, education and class of different electoral wards (https://www.theguardian.com/politics/ ng-interactive/2016/jun/23/eu-referendum-live-results-and-analysis). The Guardian’s analysis stopped at showing these results graphically, and commenting on the apparent patterns. We will go one better by doing some real statistical analysis of the data.

I have scraped the data from the Guardian’s plots into a data file (brexit.csv).

There are 6 attributes in the data. The 5 possible input variables are:

abc1: proportion of individuals who are in the ABC1 social classes (middle to upper class)
medianIncome: the median income of all residents
medianAge: median age of residents
withHigherEd: proportion of residents with any university-level education
notBornUK: the proportion of residents who were born outside the UK
These are normalised so that the lowest value is zero and the highest value is one. The output variable is called voteBrexit, and gives a TRUE/FALSE answer to the question ‘did this electoral ward vote for Brexit?’ (i.e. did more than 50% of people vote to Leave?).

Project 3:
Can I eat that mushroom?

classic machine learning data set? When researchers create new methods they typically test their performance
on data sets people have looked at before, so that the prediction accuracy can be benchmarked against
existing methods. This means that certain data sets appear time and time again in research. One of these is
the famous ‘mushroom data set’: a set of observations about different specimens of gilled mushrooms in The
Audubon Society Field Guide to North American Mushrooms (1981). Each specimen is measured in terms of
some visual and olfactory information, such as its Cap Size and its Odor type. They are also labelled as
being edible or poisonous. Our goal is to determine whether a mushroom is edible from its characteristics.


There are 6 attributes in the data, all of which are factors (non-numeric categorical variables). These are:
Edible (to be predicted), CapShape, CapSurface, CapColor, Odor and Height. 
