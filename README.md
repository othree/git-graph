Gitdags Samples
===============

Generate
--------

    ls *.tex | xargs -I {} pdflatex {}
    ls *.pdf | xargs -I {} pdf2svg {} {}.svg
