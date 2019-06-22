# Latex Doc template
A latex doc formatted according to the scientific publication requirement.

### Demos:

1. A link to an online automatic latex build system: [latexonline.cc](https://latexonline.cc/compile?git=https%3A%2F%2Fgithub.com%2Fhol137%2Fdoc-latex&target=main.tex&command=pdflatex), [latexbase.com](https://latexbase.com) or try [OverLeaf](https://www.overleaf.com/)

| Latex Doc Type                |      "*.sty"                 |        "*.tex"              |      Compile in PDF                                                                                                                                    |
| ----------------------------- |:----------------------------:|:---------------------------:|-------------------------------------------------------------------------------------------------------------------------------------------------------:|
|Scientific publication Format  |[e-journal.sty](e-journal.sty)| [main.tex](main.tex )       |[latexonline.cc main.tex](https://latexonline.cc/compile?git=https%3A%2F%2Fgithub.com%2Fhol137%2Fdoc-latex&target=main.tex&command=pdflatex)      |
|Scientific publication Test  |[e-journal.sty](e-journal.sty)| [test.tex](test.tex )       |[latexonline.cc test.tex](https://latexonline.cc/compile?git=https%3A%2F%2Fgithub.com%2Fhol137%2Fdoc-latex&target=test.tex&command=pdflatex)      |


**The project files:**
======

- 1.0 **e-journal.sty** - the journal style file.
- 2.0 **main.tex** - the main template file.
- 3.0 **figures** - the directory which should contain your figures.

**Usage notes:**
======

1. The "main" file is the **main.tex**, thus, to render a pdf, run **main.tex**.
2. Your personal information, date can be configured in the main file.
3. The main file also defines the structure, order and numbering of the thesis title pages.
4. The main file define the doc content and order - starting from "\begin{document}"
5. The main file defines all needed keywords - don't hesitate to remove unneeded definitions.


**General Notes:**
======

1. You can use, redistribute and do whatever with this project, however, the author takes no responsibility whatever usage of this project.
2. If you start another project based on this project, it would be nice to mention/link to this project.
3. You are very welcome to contribute to this project.
