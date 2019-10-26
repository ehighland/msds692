# Polls and Polarity
### A project for my Regis University Data Science Practicum 1

#### Background
This project was started because I was curious how different populations view the top three Democratic
presidential candidates. Joe Biden, Bernie Sanders, and Elizabeth Warren consistently poll
as the top three, but not always in the same order.

#### Process
I used sentiment polarity analysis on mined Twitter data to get a sense of how random Twitter users view the three candidates. I used opinion poll ordering, taken from reputable sources from FiveThirtyEight, to gauge the opinions of these poll takers. These were my two populations of interest. I used various ML approaches to determine if the populations agreed. I did this by gauging how successful summary statistics about the sentiment polarity scores were at predicting the poll ordering.

#### Conclusion
I do not believe that the predictions herein can be considered fully reliable, but there are some
slight correlations shown. These correlations can be compared to those uncovered by the Tableau
viz, found here. I found that less of a correlation is shown in the Tableau viz than [shown here](https://public.tableau.com/profile/emma.highland#!/vizhome/MSDS692/Pollcomparison). The
visualized time series only shows a pattern (an inverse correlation) withWarren, where the Twitter
sentiments become less positive over time, while her poll order rises. Sanders has stagnated in his poll ordering, as shown here as well with the consistency of his 3rd place prediction. His
sentiment scores have become slightly more positive over time, but I would have expected the
positive sentiment to correlate with rising poll order. This did not occur. Biden goes through
patches of more positive and more negative sentiments, but this does not correlate positively or
negatively with the changes in his poll order. He has only vacillated between 1st and 2nd, rather
than the range and rise shown by Warren.


I conclude that the populations (poll takers and randomly-chosen Twitter users) have distinct
opinions that do not follow the same trend.
