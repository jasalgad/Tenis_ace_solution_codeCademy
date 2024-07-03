# Tennis_ace_solution_codeCademy
First of all I take a look the data, with .describe() I could see some statistic values of some variables in order to stay alert about the important vartiables.

With the function pd.pairwaise() I check any relationship that could have any variables with others in order to make test prediction and linear regression that will gie me an high score value. As you can see on the graph, I choose the one's that could be more relevant on the previus analysis.

I choose two of them that I guess will give me a high score in order to make a good prediction: ServiceGamesPlayed', 'BreakPointsOpportunities'

Those give me:
Prediction score wins vs BreakPointsOpportunities : 0.84
Prediction score wins vs ServiceGamesPlayed: 0.89

Those are big enough to have a right results on predictions.

Take a look!
