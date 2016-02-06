# LaTeX Friendly Formatting

A very simple macro for displaying centered images.

## Usage

```latex
\documentclass{article}
\usepackage{simpleimage}

\begin{document}
  \image[0.9]{filename}
\end{document}
```

The first argument is the width as a fraction of `\textwidth`, the second is the filename.

## Installation

Git clone or download the package and then symlink it into the appropriate place
(different depending on os and laTeX distibution).

```shell
ln -s $PWD ~/Library/texmf/tex/latex/local
```

Alternatively, put the `simpleimage.sty` file next to your document.
