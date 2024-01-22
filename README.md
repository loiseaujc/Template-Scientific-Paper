# Simple template for writing a scientific article with $\LaTeX$

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

This template repository also sets up some `GitHub Actions` to automatically compile the `pdf` associated with `manuscript/main/Main.tex`.
Note that this Action is only executed when changes to any files in `manuscript/main` are being pushed.
Modifications of any other file in the repository will not trigger it.
The resulting `pdf` can be found from the `Actions` tab on `github.com` by clicking on the `Summary` associated with the last `Action` executed.

## Good practices in $\LaTeX$

The folder `manuscript/main` contains the template of a paper written using $\LaTeX$.
It includes the files:
- `preamble.tex`: Import of various $\LaTeX$ packages,
- `macros.tex`: Definition of various math-related macros and (re)definition of commands.

Note that it only is a starting point.
Feel free to modify it to your convenience by adding or removing any packages or macros you want.
Numerous resources for good $\LaTeX$ practices can be found online.
You will find below a non-exhaustive list:
- [latex-advice](https://github.com/dspinellis/latex-advice) by [Diomidis Spinellis](https://github.com/dspinellis)

Here are also a few useful resources about how to make nice figures using `matplotlib`:
- [tikzplotlib](https://github.com/nschloe/tikzplotlib): A nice `Python` utility to translate `matplotlib` figure into `tikz` code that can easily be incorporated into a $\LaTeX$ document.
- [HowToMakeAPlot](https://github.com/cajohare/HowToMakeAPlot): Slides and code by [Ciaran O'Hare](https://github.com/cajohare) focused around specific examples to improve plots using `matplotlib`.
- [SciencePlots](https://github.com/garrettj403/SciencePlots): A `Python` package providing different `matplotlib` styles to format figures for scientific papers.
- [Scientific Visualization: Python + Matplotlib](https://github.com/rougier/scientific-visualization-book): An open source by [Nicolas Rougier](https://github.com/rougier) which I highly recommend!

## Reproducible research

## Miscellaneous
