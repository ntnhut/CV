## My Résumé — Written in LaTeX

This repository contains the LaTeX source for my personal résumé.

I use LaTeX to write my résumé because I treat it as a piece of code — version-controlled, reproducible, and beautifully typeset. Every change in my career history is tracked just like a software project.

### 🛠️ Features

* Clean and minimal design for professional readability.
* Fully customizable and version-controlled.
* Compatible with any modern LaTeX distribution.
* PDF build via command line.

### 🧰 Build Instructions

* This template originates from [http://www.LaTeXTemplates.com](http://www.LaTeXTemplates.com).
* `xelatex` is required to be installed on your computer.
Linux:
```
sudo apt install texlive-xetex
sudo apt install texlive-fonts-extra
```
* To compile the résumé locally:
```
xelatex -interaction=nonstopmode cv_Nhut.tex
```
It produces `cv_Nhut.pdf`. You can view it here in this repo, too.

### 💡 Why LaTeX?

* Precise control over layout and typography.
* Perfect for engineers and researchers who want structure and clarity.
* Easy to track changes using Git.
* Portable and consistent across systems.
