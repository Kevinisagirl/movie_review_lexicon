# movie_review_lexicon
An attempt at simple sentiment analysis of movie reviews
Takes a long time to run - not optimized

Based on a class assignment for NLP:

Please write an iPython notebook that implements the Turney algorithm (slide 35 and following in the Lexicon slides) to create a list of positive and negative two-word phrases from movie reviews.

For this you will use the movie reviews from this tar.gz file.

For code development just use one or two reviews. When your code works use all 1000 positive reviews and all 1000 negative reviews.

Start with a seed. You may use Turney's seed of two words, "excellent" and "poor", or you may start with a larger seed of positive and negative adjectives, e.g. by using synonyms of good and bad.

Extract two-word phrases of the form on slide 40, or forms of your choosing. Use the NLTK POS tagger.

Calculate the polarity of each phrase as on slide 45, for some nearness threshold. You may use a large corpus like this or this IMDb review database (https://ncf.instructure.com/courses/3412/files/152310/download?verifier=iXBRUC6jxhGsCUQpcxU0xIP5fDBa199VQSXGVMiP&wrap=1) (making sure there's no overlap with the test set).

Calculate the polarity of each review based on the polarities of its phrases, and compare to its label. 

In each of these four steps you may use Turney's parameters and choices or tune your own. If at any step you tune your own, tune your parameters and choices on a validation set, say 100 positive and 100 negative reviews, and test on the remaining 900 positive and 900 negative reviews.
