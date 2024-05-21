TTU PhD thesis template for LaTeX with BibTeX reference management

CONTENTS:
thesis.tex     - thesis source file (template)
thesis.pdf     - compiled example
references.bib - plaintext file in BibTeX format, containing references
                 several such files can be included
TTUPhD.cls     - class definition for TTU PhD template
./art          - contains the PDF files of the articles to be included
./img          - directory for various images


COMPILATION:
pdflatex thesis.tex
bibtex thesis
pdflatex thesis.tex
pdflatex thesis.tex

this outputs a file 'thesis.pdf'
