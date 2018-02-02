# LaTex-lncs-starter
Latex starter with lncs template for students

## Installation
Instruction to install LaTex [here](https://fr.wikibooks.org/wiki/LaTeX/Installer_LaTeX)

## Generate PDF file

### First time compilation (or biblio updated)

You need to do it the first time you generate the PDF file or when you update the bib file.

First compile your document with `pdflatex`

```bash
pdflatex paper
```

Then compile your bibtex file with `bibtex`

```bash
bibtex paper
```

Finally, recompile your document two times with `pdflatex`

```bash
pdflatex paper
pdflatex paper
```

### Compilation when you only update your document

Just compile your document with `pdflatex`

```bash
pdflatex paper
```

## How To LaTex

You will find [Here](https://fr.wikibooks.org/wiki/LaTeX) a nice doc for Latex
