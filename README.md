# Jeopardy! Topic Modeling

The game show Jeopardy! has held a place in American households for decades. In homage to the late host Alex Trebek, this project applies language parsing and topic modeling strategies to over 200,000 Jeopardy! questions sourced since 1984 when Trebek first became host.

In this project, we analyze the content of Jeopardy! questions in terms of:
1. Game Dynamics: We use LDA topic modeling to evaluate how thematic topics of the game have changed over the years.
2. Question Difficulty: Using the monetary value for each question, we compare the relative difficulty of questions across time.

We use SpaCy for text preprocessing and Latent-Dirichlet Allocation (LDA) for topic modeling. Fitted models and large variables such as word corpuses
are pickled and saved in subdirectories for user convenience.

This project is for MSDS626 - Case Studies in Data Science, in partial fulfillment of the MS in Data Science degree at the University of San Francisco.

Contributors (alphabetically):
Remi LeBlanc
Joshua Majano
Lucia Page-Harley
