%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%   Project: langsci
%%    Author: Language Science Press (http://langsci-press.org)
%%      Date: 2016-05-09 11:11:11 UTC
%%   Purpose: publishing boks with Language Science Press.
%% Languages: LaTeX, tikz, eps
%%  Copyright 2012- Language Science Press
%%  Licence: This work may be distributed and/or modified under the
%%  conditions of the LaTeX Project Public License, either version 1.3
%%  of this license or (at your option) any later version.
%%  The latest version of this license is in
%%    http://www.latex-project.org/lppl.txt
%%  and version 1.3 or later is part of all distributions of LaTeX
%%  version 2005/12/01 or later.
%%
%% This work has the LPPL maintenance status `maintained'.
%% 
%% The Current Maintainer of this work is Sebastian Nordhoff.
%%
%% This work consists of the files 
%% - langscibook.cls: class file
%% - series.def: metadata for series
%% - colors.def: colors used by the series
%% - langsci-basic.sty for commands required by the standard template
%% - bib style definitions langsci-unified.bst, biblatex-sp-unified.bbx, sp-authoryear-comp.cbx
%% - files for the logos used in the textbook series Textbooks in Language Sciences: book.eps  bulb.eps  glass.eps  law.eps
%% - the file logo.pdf as a dummy, to be replaced with a file for the hosting institution
%% - a file advertisement.tex added to the very last page in tikz
%% - langsci-optional.sty: additional useful commands
%% - langsci-gb4e.sty and langsci-cgloss.sty: typeset linguistic examples
%% - langsci-forest-setup.sty: definitions for linguistic trees
%% - langsci-bidi.sty: bidirectional text
%% - langsci-tbls.sty: macros for the textbook series Textbooks in Language Sciences
%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


Here you find files to produce books for Language Science Press

The main file is the file langscibook.cls. This defines the basic structure of the book. It makes reference to the following auxiliary files:
- `langsci-series.def`: metadata for series
- `langsci-colors.def`: colors used by the series
- `langsci-basic.sty` for commands required by the standard template
- bib style definitions
- eps files for the logos used in the textbook series Textbooks in Language Sciences 
- a file for an advertisement added to the very last page in tikz

The following optional packages are also provided, but have to be included manually if desired:
- `langsci-optional.sty`: additional useful commands
- `langsci-gb4e.sty` and langsci-cgloss.sty typeset linguistic examples
- `langsci-forest-setup.sty`: definitions for linguistic trees
- `langsci-bidi.sty`: bidirectional text
- `langsci-tbls.sty`: macros for the textbook series Textbooks in Language Sciences

Documentation is found in the folder `documentation/`.

The folder `examples/` contains sample projects for the three use cases monograph, edited volume, and paper in edited volume.

For more information, visit \url{http://www.langsci-press.org}.


