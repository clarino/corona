# corona
Analysis of corona compounds from the Norwegian Newspaper Corpus
by Koenraad De Smedt, University of Bergen.

All files contain items occurring as the second part of compounds
starting with *corona* or *korona*.
Possible hyphens have been stripped.
All items have been case-folded by downcasing.

Example: *virus* aggregates occurrences of *coronavirus, koronavirus,
corona-virus, korona-virus, Coronavirus, Koronavirus, CORONA-VIRUS,* etc.

Additionally, lemmatized lists aggregate occurrences of inflected forms.
Example: *virus*, *viruset*, *virusets*, *virusene*, etc.

This updated version is based on materials from CLARINO Corpuscle
covering the period from January 1 until May 26, 2020.

A further description and analysis of these data will be presented
in forthcoming papers.

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