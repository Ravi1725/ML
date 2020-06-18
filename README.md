QUESTION:-
Identify Question Type: Given a question, the aim is to identify the category it belongs to. The four categories to handle for this assignment are : Who, What, When, Affirmation(yes/no).
Label any sentence that does not fall in any of the above four as "Unknown" type.
You should come up with data structures to encapsulate these information as well as the code that populates the relevant data. You can use any machine learning technique and use the attached labelled data set for learning.

Examples:-
1. What is your name? Type: What
2. When is the show happening? Type: When
3. Is there a cab available for airport? Type: Affirmation
There are ambiguous cases to handle as well like:
What time does the train leave(this looks like a what question but is actually a When type)

DEPENDENCIES:-
python = 3.8.0
keras = 2.0.8
tensorflow = 1.1.0
numpy = 1.13.1
pandas = 0.20.2
sklearn = 0.18.1
argparse
re
json
random
pickle

IN this program GLOVES pretrained model for word embedding, from that download file(glove.42B.300d.txt) the link is http://nlp.stanford.edu/data/glove.42B.300d.zip.

Also add model.json file in folder.

For Execution of Program:
1.Training program--python3 training.py

2.Run program--python3 run.py
