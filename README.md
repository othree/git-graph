Gitdags Samples
===============

Generate
--------

    ls *.tex | xargs -I {} pdflatex {}

Conver to SVG
-------------

    ls *.pdf | xargs -I {} pdf2svg {} {}.svg

or

    ls -d -1 $PWD/*.pdf | xargs -I {} inkscape --without-gui --file={} -T --export-plain-svg={}.svg
