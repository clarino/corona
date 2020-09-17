# corona
Analysis of corona compounds from the Norwegian Newspaper Corpus.

Items occurring as the second part of compounds starting with *corona* or *korona*.
Possible hyphens have been stripped.
All items have been case-folded by downcasing.

Example: *virus* aggregates occurrences of *coronavirus, koronavirus, corona-virus, korona-virus,
Coronavirus, Koronavirus, CORONA-VIRUS,* etc.

This updated version is based on materials from CLARINO Corpuscle that cover the period from January 1 until May
26, 2020.

## Files:

*korona-freq.csv* = frequency list of items, ordered by decreasing frequency

*korona-compounds.csv* = types by date of first occurrence, also including source; if an item
appeared in different sources on the same date, only one source is given.

These character separated files have TAB as field separator.