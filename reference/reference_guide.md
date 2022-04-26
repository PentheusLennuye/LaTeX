# Paragraphs

## Paragraph Example 1

...when Einstein introduced his formula $$e = m \cdot c^2 \; ,$$ which
is at the same time the most widely known and the least well understood
physical formula.

## Paragraph Example 2

...from which follows Kirchhoff's current law:
$$\sum_{k=1}^{n} I_k = 0 \; .$$

Kirchhoff's voltage law can be derived ...

## MBoxes

MBoxes ensure that a block of text remains on the same line. For
example, the telephone number here is wrapped in an` \mbox{}`:
(450) 330-4742.

## Ready-Made Strings

\\today = 2022-04-26\
\\TeX = TeX\
\\LaTeX = LaTeX\
\\LaTeXe =\

# Special Characters and Symbols

## Quotation Marks

\`\`Please press the \`any\' key. \'\' = "Please press the 'any' key."

## Dashes and Hyphens

daughter-in-law, X-rated = daughter-in-law, X-rated (hyphen)\
pages 13 - - 67 = pages 13--67 (en-dash)\
yes - - - or no? = yes---or no? (em-dash)\
\$0\$, \$1\$ and \$-1\$ = $0$, $1$ and $-1$ (minus)

## Tilde

\\\~{} gives a regular tilde: \~\
For the web, use \$\\sim\$: http://cummings-online.ca/$\sim$george

## Slash between words

read\\slash write = read/write

## Euros

\\usepackage\[official\]{eurosym}\
\\euro = €

## Ellipsis

\\ldots = ...

## Suppress Ligatures

ff, fi, fl, ffi: use f\\mbox{}l to get fl.

# References

## Cross References

### Target

Use \\label{*identifier*}. For example, a reference to this
[]{#examplelabel label="examplelabel"} subsection uses
\\label{examplelabel}.

### Cross Reference

Now we can refer to the previous target with \\ref{examplelabel} on page
\\pageref{examplelabel}. For example, section
[\[examplelabel\]](#examplelabel){reference-type="ref"
reference="examplelabel"} on page .

## Footnotes

Really easy. Just append \\footer{*Reference Text*} to the word being
referred to. For example, "Foxes are not elephants"[^1].

# Environments

## Verbatim

This would be important for programming, I suppose.\
`\begin{verbatim}` ...`\end{verbatim}`\
Example:\

    import os

    for i in 'thing whump fweep'.split():
        with open(os.path.join(CURDIR, i), 'r') as fp:
            fp.read()

# Appendix Example

This is an example appendix.

[^1]: Theodore Seuss, *Horton Hears a Who*, p.12
