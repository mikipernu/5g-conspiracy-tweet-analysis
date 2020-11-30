# Jupyter Notebook files

This project uses three Jupyter workflows for a) creating a list of words that can be used for finding and tagging conspiratory content and b) processing a data set for its conspiratory content.

First, we use the file `5g-conspiratory-data-sets.ipynb` to combine data sets into a data set with confirmed conspiratory content.

Second, we process the data set with `5g-conspiracy-stop-words.ipynb` and conspiratory content into tag words for analyzing the larger data set we want to analyze.

Last, we clean the data set we're analyzing with `5g-text-cleaning.ipynb`. This workflow also finds and tags conspiratory content and creates two data sets: one with conspiratory content and one without. Then it analyzes both for the most common words and hashtags, most important words and hashtags (with [tf-idf](https://en.wikipedia.org/wiki/Tf%E2%80%93idf)), and make a sentiment analysis with [Vader](https://github.com/cjhutto/vaderSentiment).
