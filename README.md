# 2020 Election Prediction Model

I wanted to a method to estimate Biden's and Trump's chances of winning the election.

To do this I took the latest good quality poll in each state, calculated a margin of error, probabilistically selected a winner for each state, tallied up the electoral college votes, determined won the election, and repeated this process 100,000 times.

##  Notes and Assumptions
1. Only "swing states" are included in the analysis. I am assuming that Biden has 185 votes and Trump has 127 votes locked up.
2. States are totally independent of each other. This is not true in reality. For example, if Biden wins Florida, he is more likely to win Georgia. However, I am assuming that the polls are independent of each other.

## Results
Biden wins 99.x% of the time. The model is not perfect, but it is good enough for me to make a bet

## Todo
- [ ] Formalize the math and equations
- [ ] Compare the poll snapshot to the election results
- [ ] Run on 2024 election polls when they are available