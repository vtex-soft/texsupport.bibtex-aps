# texsupport.bibtex-aps

## About

This package provides American Physical Society (APS) BibTeX reference style 
(`aps-nameyear.bst`) for Springer journals. There are also included few example files 
(`.tex`, `.bib`, `.pdf`) showing how to use BibTeX style file and how it would look like.

## Contents

The following files are given in the repository (or directly in `.zip` archive):

-   `aps-nameyear.bst` - BibTeX style for author-year citations; 
-   `aps-bibstyle.sty` - LaTeX macro commands for APS bibliography; 
-   `template.tex`  - template file; 
-   `template.pdf` - journal sample article with APS bibliography;
-   `example.bib` - BibTeX database file.

## Setup

-   Clone the repository or download the `.zip` archive;
-   Install `aps-nameyear.bst` and `aps-bibstyle.sty` in your LaTeX system or 
    place them in the same directory where your `.tex` file is;
-   use the file `template.tex` to start your article as a template;
-   **Important**: `template.tex` uses `svjour3.cls` LaTeX style file, 
    which couild be downloaded from [Springer site](http://static.springer.com/sgw/documents/468198/application/zip/LaTeX_DL_468198.zip).

## Comments

-   BibTeX file `aps-nameyear.bst` is compatible only with `natbib` package.
-   The `natbib.sty` package is an extension to LaTeX to allow author-year citations along with numerical citations.
-   It's available in all LaTeX distributions. Read the `natbib` manual for various types of citation commands.
-   You can find the manual in [CTAN page](https://www.ctan.org/pkg/natbib).
-   Or you can try to type in command line:
        
        texdoc natbib

    If you use a standard TeX distribution, the PDF manual should show up. 

## Bug reports

Please submit bug reports and/or feature requests
at [GitHub page](https://github.com/vtex-soft/texsupport.svjour-aps-nameyear/issues) or 
[latex-support@vtex.lt](mailto:latex-support@vtex.lt).

