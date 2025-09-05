# Some useful LaTeX sty and bib files

## 1. SH_acronyms.sty

It includes acronyms used in the book. Include the following line at the beginning of the document.

```
\usepackage{SH_acronyms}
```

## 2. SH_string.bib

Include this string definition before your main bib file.
```
\bibliography{SH_string,your_bibliography}
```
Then, from the bib file, you can use the string for SLAM-related conferences and journals. For example,

```
@Article{cadena2016past,
  author        = {Cadena, Cesar and Carlone, Luca and Carrillo, Henry and
                  Latif, Yasir and Scaramuzza, Davide and Neira, Jos{\'e} and
                  Reid, Ian and Leonard, John J},
  title         = {Past, present, and future of simultaneous localization and
                  mapping: Toward the robust-perception age},
  journal       = tro,
  year          = 2016,
  volume        = 32,
  number        = 6,
  pages         = {1309--1332},
  publisher     = {IEEE}
}
```
