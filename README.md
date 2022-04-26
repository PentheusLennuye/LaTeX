# LaTeX

This is my education on all things LaTex, including converstion to other
formats such as HTML, Markdown, etc.

## pdflatex and bibliographies

PDFLatex will not work with *biber* for bibliographiers with one go. In a
nutshell, use the following commands:
```
pdflatex <filename.tex>
biber <filename>  # No 'tex'
pdflatex <filename.tex>
pdflatex <filename.tex>
```

## pandoc

Pandoc converts from format to format, including LaTeX.
```
pandoc -out README.md -t gfm README.tex
```
