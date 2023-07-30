# Elections 2024 Precog Application
### Nanda Rajiv

## A. Analysis

#### i. Regionalism, Assembly Elections and Voter Turnout
Using the dataset provided, we can gather observations about the 2014 and 2019 elections, which are crucial to gaining better understanding of the upcoming 2024 general election. 


One of the major factors that are likley to influence 2024 is the rise of regionalism. From the dataset provided (Ashoka University's Lok Dhaba), we can use datasets of the last two general elections, as well as additional datasets collected on Assembly Elections of all states in recent years, to evaluate the voter turnout. This could give insights about perceptions of voters on their impact on national issues, and gives ideas on whether and how regional parties cater better to these areas which are increasingly beginning to influence the course of the next national election.
<br/>

#### ii. Education and Success in Elections

The dataset provides a column that contains details of a candidate's educational background, such as whether a candidate has a doctorate, post gradaute, 10th pass, 8th pass,or whether they are a graduate professional, or illiterate, etc. <br/>
This datapoint could be weighed against candidates' success, to find out what appeals to voters. <br/>

To expand the scope of this exercise beyind just a candidate winning or not winning, since win margins may be very low among top candidates, and losing by a small margin is also some measure of success, the factor considered is the <b>security deposit</b>.

A candidate recieved their security deposit back only if they have gotten greater than 1/6th of the valid votes in their constituency for a general election in India, and this is the measure used here for a successful candidature.
<br/>

#### iii. Win Margin and Turnout Percentage

There have been reports on a correlation between high voter turrnout and greater margins of victory in recent assembly elections in various states. This has been a debate that came up after a recent Tamil Nadu assembly election. <br/>
The dataset provided can be used to evaluate this claim and see if it is extendable to the Lok Sabha elections.

On selecting the top performing candidates in each constituency, and seeing their margins of victory, we can actually see that it is fairly independent. By and large, the margins of victory is very low, despite a range of turnour percentages. There was no observable relationship for 2014 and 2019 in terms of win margin and turnout percentage.

## B. Classification

The problem chosen is to identify whether a certain candidate is a member of a national party or not. In light of the rise of regionalism, and as national colaitions increasingly vie for regional parties support and endorsement in order to secure stronghold in states that otherwise do not often feel very represented in national elections, gaining understading of correlations between a candidate being of a national party and their success could be an important task.

## C. Paper Reading 

The paper read was 'Framing and Agenda-setting in Russian News: a Computational Analysis of Intricate
Political Strategies'. The report on the paper can be found in the folder reading_task. 

## D. Instructions to Run Code

Dependencies used include pandas, numpy, scikit-learn, matplotlib, etc. 
Before running the code, please ensure the paths and filenames are correct, and all dependencies are installed. 
