UET FYP DESIGN DOCUMENT TEMPLATE
================================

This project uses the supplied UET thesis class and is ready for Overleaf.

OVERLEAF
1. Upload the complete ZIP through New Project > Upload Project.
2. Confirm that uet_thesis.tex is selected as the Main document.
3. Use the pdfLaTeX compiler and select Recompile.

PROJECT STRUCTURE
- uet_thesis.tex: main file; edit title-page details and compile this file.
- uet_thesis.cls: university formatting class; do not edit.
- Chapters/: chapter and appendix source files.
- Figures/: UET logo and all project figures.
- references.bib: BibTeX references cited from the chapters.
- uet_thesis.lof and uet_thesis.lot: generated list-of-figures and
  list-of-tables files; do not edit manually.

STUDENT INSTRUCTIONS
- Replace all blue placeholders and remove all marked examples.
- Retain conditional sections only when they apply to the project type.
- Put each new figure in Figures/ and use a clear filename.
- Add references to references.bib and cite them in the relevant chapter.
- Keep detailed test cases and results in the separate testing document.
- Compile uet_thesis.tex after every major update and resolve all errors.

ADDING CONTENT
- Add a chapter file to Chapters/ and include it from uet_thesis.tex.
- Add an image with, for example:

  \begin{figure}[htbp]
    \centering
    \includegraphics[width=0.8\textwidth]{figure-name}
    \caption{Clear figure caption}
    \label{fig:clear-label}
  \end{figure}

Do not rename or modify uet_thesis.cls unless the department issues an updated
class file.
