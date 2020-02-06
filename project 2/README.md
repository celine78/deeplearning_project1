# deeplearning_projects
projects one and two by Patrick Grosschmidt, Cristiano Colangelo, Sylvain Barthe, Chadi Taieb, Céline Hüttenmoser

Task 4

What would be a way to utilize this data in order to generate larger lists of false positives?

We should inspect those files and try to understand where the learning algorithm is failing, trying to find patterns in the reviews that can trigger a wrong prediction. Perhaps the reviewer used irony or there could be some ambiguity/bias.

Derive a method that will allow you to predict over the full content of the file:

In order to detect false positive predictions we used following words: 'but', 'unfortunately' and 'fake'.
To detect false negative reviews we used the words: 'but', 'great', 'good', 'cool' and 'love'

As stated above, many reviews contained some ambiguity. This was especially the case for the negative ones, which could explain why we found so many cases of false positive predictions. In those texts, reviewers would often begin their critic by stating what they liked about the product, before adding a 'but' or 'unfortunately' which then lead to a general negative review. However, the learning algorithm did not always detect these subtleties.

Task 5

precision = true positives / true positives + false positives
True positive count = 622
False positive count = 1038
Precision = 0.37