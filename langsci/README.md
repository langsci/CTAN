Here you find files to produce books for Language Science Press

The main file is the file langscibook.cls. This defines the basic structure of the book. It makes reference to the following auxiliary files:
- `series.def`: metadata for series
- `colors.def`: colors used by the series
- `langsci-basic.sty` for commands required by the standard template
- bib style definitions
- eps files for the logos used in the textbook series Textbooks in Language Sciences
- the file `logo.pdf` as a dummy, to be replaced with a file for the hosting institution
- a file for an advertisement added to the very last page in tikz

The following optional packages are also provided, but have to be included manually if desired:
- `langsci-optional.sty`: additional useful commands
- `langsci-gb4e.sty` and langsci-cgloss.sty typeset linguistic examples
- `langsci-forest-setup.sty`: definitions for linguistic trees
- `langsci-bidi.sty`: bidirectional text
- `langsci-tbls.sty`: macros for the textbook series Textbooks in Language Sciences

Documentation is found in the folder `documentation/`.

The folder `example/` contains sample projects for the three use cases monograph, edited volume, and paper in edited volume.

For more information, visit http://www.langsci-press.org


