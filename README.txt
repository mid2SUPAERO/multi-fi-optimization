ISAE-Supaero LaTeX/Beamer template for presentations


INTRODUCTION
------------
This LaTeX/Beamer template has been designed in order to help students 
writing their presentations. A skeleton is already proposed in French.


REQUIREMENTS
------------
 A full LaTeX distribution such as TexLive (>2012) or MikTex (>2012).
 An UTF-8 aware text editor such as TexMaker or Emacs.
 Optionally: a bibliography manager such as JabRef can be used in order
to edit the .bib file.


USAGE
-----
 Edit the {.tex,.bib} files using UTF-8 encoding.
 Rename the .tex file according to your presentation topic.
 Put your figures in the "images" subdirectory.

The compilation process is the following:
1) Compile the main file "isae-beamer-template.tex" using PDFLatex.
2) Compile the "isae-beamer-template.aux" using BibTeX.
3) Compile twice the main file "isae-beamer-template.tex" using PDFLatex.


FILES MANIFEST
--------------
 "isae-beamer-template.tex": main LaTeX file of the presentation.
 "isae-beamer-template.pdf": main output file of the presentation. 
 "references.bib": bibliography database used by default.
 "authoryear-fr": a bibliography style file used by default.
 "images": subdirectory used to store the figures.
 "README.txt": the current file.


EXTERNAL DOCUMENTATION
----------------------
Discovering the language with "A not so short introduction to LaTeX":
<http://ctan.mines-albi.fr/info/lshort/english/lshort.pdf>

Doing you own figures in LaTeX using "TikZ for the impatient":
<http://math.et.info.free.fr/TikZ/bdd/TikZ-Impatient.pdf>

Getting inspired by already on-the-shelf figures via "TikZ examples":
<http://www.texample.net/tikz/examples/>

Doing math plotting using "PGFPlots":
<http://pgfplots.sourceforge.net/pgfplots.pdf>

Exporting you Matlab plots thanks to "Matlab2TikZ":
<https://github.com/nschloe/matlab2tikz>


CREDITS
-------
This template has been created by Damien Roque (ISAE Supaero)
<damien.roque_AT_isae-supaero.fr>


CHANGELOG
---------
 09/29/14 v0.1 Initial version.
 11/12/14 v0.2 Small changes in the README.txt file.
