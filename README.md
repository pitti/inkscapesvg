inkscapesvg
===========

A LaTeX package for including SVG images using inkscape on-the-fly conversion.


Usage
=====

```TeX
\usepackage{inkscapesvg}

% optional graphicspath
\graphicspath{{images/}}

% ...

\includesvg[width=1.0\textwidth,fsize=\small]{my-svg}
```
