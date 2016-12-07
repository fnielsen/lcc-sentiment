lcc-sentiment
=============

Sentiment annotation of The Leipzig Corpora Collection.

Manual sentiment annotation by Finn Årup Nielsen of Danish sentences.

Data
----
The data is directly derived from The Leipzig Corpora Collection which is downloadable from http://corpora2.informatik.uni-leipzig.de/download.html.
The format in the data files is changed slightly from tab-separated to comma-separated and an column header is added.
An extra column is introduced called 'valence'.
This contains the sentiment scoring. 
The scoring follows the pattern from AFINN with integer scoring from -5 to +5,
though for most sentence, if any, the full range of the score is not used. 

An example in Python with the Pandas for reading the data with the read_csv function is shown in the Jupyter Notebook.


Citation
--------
The citation to the unannotated Leipzig Corpora Collection is

Quasthoff, U.; M. Richter; C. Biemann: Corpus Portal for Search in Monolingual Corpora, Proceedings of the fifth international conference on Language Resources and Evaluation, LREC 2006, Genoa, pp. 1799-1802.

There is presently no citation to a scientific paper for the annotation. 

See also
--------
https://github.com/fnielsen/europarl-da-sentiment


References
----------
http://corpora2.informatik.uni-leipzig.de/download.html
