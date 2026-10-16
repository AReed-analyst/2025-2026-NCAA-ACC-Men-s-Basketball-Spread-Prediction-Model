Hi ACC CBB Enjoyers!

This project was for the 2026 Triangle Sports Analytics Competition. I decided to utilize the SRCBB 
(https://www.sports-reference.com/cbb/) and Barttorvik (https://barttorvik.com/trankpre.php) databases
to predict both the final spread and the confidence intervals across the 78 ACC Men's College Basketball
games from February 7th to March 7th of 2026. 

The Excel sheet contains the final predictions and much of the simple algebraic calculations while
the Python workbook has the Pace calculations for all of the teams (using a weighted rolling average).

In the Excel sheet, you'll notice some scores highlighted in yellow and some highlighted in blue, while 
some aren't highlighted at all. The no-highlight were the scores for games that happened prior to February
7th (testing data) and the highlighted games were the ones I was predicting. I decided to redo my model 
about halfway through the competition's timeframe to see if I could improve my final Mean Average Error,
which are the scores highlighted in blue. 

My final MAE was 9.0454 points, and I hope to improve this model for future seasons and more conferences!
