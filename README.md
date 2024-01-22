# README

This is a template repository for writing scientific papers, most notably with $\LaTeX$.
The structure of the repository is shown below.


```
.
├── data
├── manuscript
│   ├── archives
│   ├── cover letter
│   └── main
├── notebooks
├── papers
├── plots
├── scripts
├── src
└── test
```

Each of these folders serve the following purposes:

- `data`: This folder contains all the (pre-processed) data needed for generating the different figures.
- `manuscript`: This folder contains all the files related to the manuscript.
  - `archives`: This folder contains the archived versions of the manuscript as well as the communications with the journal to which it has been submitted.
  - `cover letter`: This folder contains the cover letter send to the editor of the journal.
  - `main`: This folder contains the current version of the manuscript.
- `notebooks`: This folder contains all the illustratory notebooks provided as supplementary material (if any).
- `papers`: This folder contains (whenever possible) the pdf of the different articles cited in the manuscript.
- `plots`: This folder contains all of the plots included in the manuscript as well as those possibly generated for seminars and presentations.
- `scripts`: This folder contains all the scripts (e.g. `Python`, `R`, or `Julia`) needed to regenerate the figures.
- `src`: This folder includes all of the source code (`Julia`, `Python`, `Fortran`, etc) needed to re-run the computations.
- `test`: This folder contains all the tests (if any) used to validate the different implementations.

## Good practices in \LaTeX

The folder `manuscript/main` contains the template of a paper written using \LaTeX.
It includes the files:
- `preamble.tex`: Import of various \LaTeX packages,
- `macros.tex`: Definition of various math-related macros and (re)definition of commands.

Note that it only is a starting point.
Feel free to modify it to your convenience by adding or removing any packages or macros you want.

## Reproducible research

## Miscellaneous
