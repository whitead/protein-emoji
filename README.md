# Protein Emoji

Files and utilities for protein-emoji

## LaTeX

To use the emoji in your LaTeX documents:

```tex
\documentclass[12pt]{article}
\usepackage{graphicx}

\newcommand{\protein}{%
  \begingroup\normalfont
  \raisebox{-0.25\baselineskip}{\includegraphics[height=\baselineskip]{images/protein-72-color.png}}%
  \endgroup
}

\begin{document}
Hello world\protein{}! 
\end{document}
```


## License for Images
[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)
License will change if protein is approved by subcommittee to have no attribution required. 
## Copyright
(c) 2022 University of Rochester