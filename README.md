# korona20 / corona21
Analysis of corona compounds from the Norwegian Newspaper Corpus
by Koenraad De Smedt, University of Bergen.

## Two version are available, each in its directory:

- korona20 covers a period from January 9, 2020 until May 26, 2020. These data are described and analyzed in: De Smedt, Koenraad. 2020. “Smittsomme Koronaord.” Oslo Studies in Language 11 (2): 59–73. https://doi.org/10.5617/osla.8488.

- corona21 covers a period from January 9, 2020 until March 8, 2021. These data will be described in
a forthcoming paper.

All files contain items occurring as the second part of compounds
starting with *corona* or *korona*.
Possible hyphens have been stripped.
All items have been case-folded by downcasing.

Example: *virus* aggregates occurrences of *coronavirus, koronavirus,
corona-virus, korona-virus, Coronavirus, Koronavirus, CORONA-VIRUS,* etc.

Additionally, lemmatized lists aggregate occurrences of inflected forms.
Example: *virus*, *viruset*, *virusets*, *virusene*, etc.

A further description of the data and its analysis of these data 
is presented in forthcoming papers.

## Files:

*korona-freq-forms.csv* = frequency list of word forms, ordered by
decreasing frequency

*korona-freq-lemmas.csv* = frequency list of lemmas, ordered by
decreasing frequency

*korona-compounds-forms.csv* = word forms by date of first occurrence,
also including source;
if an item appeared in different sources on the same date,
only one source is given.

*korona-compounds-lemmas.csv* = lemmas by date of first occurrence,
also including source;
if an item appeared in different sources on the same date,
only one source is given.

All these character separated files have TAB as field separator.