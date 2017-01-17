# highLow-Quizgame
A game where you and a couple of bots guess your way towards one correct numeric answer.

A quizmaster asks a question that has a numeric answer, for example "How many teams play in the four top divisions in the english football?"
(Answer is 92, dammit.)

You and the bots takes turn guessing, and for each answer, the quizmaster indicates if it is correct, or if the correct answer is higher than the guess, or lower than the guess.
By doing so for some rounds, the limits of the "higher" and "lower" gets more and more narrow, until someone gets it right.

The user selects the number of contestants (excluding him-/herself), and the questions and answers are fetched from a database table, and also the desired number of bots.
