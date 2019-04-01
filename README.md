# latex

LaTeX class and additions for typesetting books to be published with Language Science Press

This repository contains the most recent development build. See the [skeletons](https://github.com/langsci/latex-skeletons) repository for ready to use templates.

## class options of langscibook.cls

option | values (defaults in bold face) | meaning
-------|--------|---------
booklanguage | **english** | set language of the book
collection | | for making the book an edited volume
collectionchapter | | add chapter prefix to each contribution
collectiontoclong | | more detailed table of content in edited volumes
copyright | **CC-BY** \| CC-BY-ND | choice of copyright
draftmode | | switch to draft mode (adds: draft stamp, indication of overlong lines, date) 
isbnsoftcover | \<isbn\> | the ISBN of the soft cover release
isbnsoftcoverus | \<isbn\> | the ISBN of the US version of soft cover release (used for distribution to US academic institutions)
isbnhardcover | \<isbn\> | the ISBN of the hard cover release 
modfonts |  | use LangSci fonts
multiauthors |  | use eds. instead of ed.
nonflat |  | load additional files from a local folder instead of standard paths
number | \<number\> | number of the book within the series
openreview | | switch to open review mode
output |  **book** \| inprep \| paper \| guidelines  \| coverbodhc \| coverbodsc \| covercreatespace | different output formats
series | sidl \| **eotms** \| ... | the series code (see langsci-series.def for a list of abbreviations)
showindex | | show index commands on margin
smallfont | | use 10pt as fontsize
url | \<url\> | the URL of the book 
