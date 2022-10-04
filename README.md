# Protein Emoji

Files and utilities for the 2022 proposed protein emoji. 

<img width=72 src="./src/protein-72-color.svg">

## Files

The SVGs are available in [`src`](./src) and the PNGs are in the root. 

## LaTeX

<img width="116" alt="Screen Shot 2022-10-04 at 9 29 52 AM" src="https://user-images.githubusercontent.com/908389/193862016-f5f26c92-2305-46e3-8d4a-f94e90c58eeb.png">


To use the emoji in your LaTeX documents:

```tex
\documentclass[12pt]{article}
\usepackage{graphicx}

\newcommand{\protein}{%
  \begingroup\normalfont
  \raisebox{-0.25\baselineskip}{\includegraphics[height=\baselineskip]{protein-72-color.png}}%
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
