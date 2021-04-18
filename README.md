# LaTeX presentation template for Medical Center - University of Freiburg
A LaTeX template for presentations in the name of the [Medical Center - University of Freiburg im Breisgau](https://www.uniklinik-freiburg.de/de.html). This is **not** an **officially** distributed template, but only create by me for in-house usage. If anyone else wants to use it, please check whether you have the permissions from the Medical Center - University of Freiburg!

# Requirements
To create a PDF with a presentation it is required to have installed
- [LaTeX](https://www.latex-project.org/)
- [beamer](https://www.ctan.org/pkg/beamer)
- [BibLaTeX](https://www.ctan.org/pkg/biblatex)
- Optionally: A LaTeX editor like [TeXstudio](https://www.texstudio.org/)

# Project structure
- ```presentation.tex``` is the file where the presentation is defined.
- In ```beamer-template.tex``` the style of the presentation is defined. You should not change this file, unless you exactly know what you do. Otherwise this might mess up your presentation.
- ```beamer-template-colorful.tex``` is like ```beamer-template.tex```, but different colors were used to prettify the presentation. This first lines in ```presentation.tex``` are
  ```
  %\input{beamer-template-colorful} % More colorful presentation
  \input{beamer-template} % Traditional colors presentation
  ```
  If you want to activate the more colorful style, change them to
  ```
  \input{beamer-template-colorful} % More colorful presentation
  %\input{beamer-template} % Traditional colors presentation
  ```
 - ```references.bib``` includes references for the bibliography. Insert all references you have there in BibLaTeX style.

# Create presentation
If you have the requirements and TeXstudio installed, open ```presentation.tex``` and press F5. This will create a file ```presentation.pdf```, which is your presentation.
