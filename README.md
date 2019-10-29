# alias-thesis

A LaTeX project for my master's thesis.

## Setup

This project has been set up for use with Visual Studio Code. It contains some settings tailored for text editing. For other programs, I suggest pulling out the `bin` folder.

Internally, the LaTeX project uses `pdflatex` with `biber` as the backend and `biblatex` as the bibliography management system.

### Requirements

- A LaTeX distribution provided in the system PATH. For Windows, TeX Live and MikTeX provides this.
- Visual Studio Code

### Install

Clone the repository

```
git clone https://github.com/idars/alias-thesis
```

Install the following extenstions for Visual Studio Code:

- LaTeX Workshop
- Code Spell Checker

Highlight a tex file, access LaTeX in the Activity Bar (`Ctrl + Alt + X`) and use the `latexmk` recipe found in `Build LaTeX project`. Then, view the PDF file with `Ctrl + Alt + V`.

## Output

The generated PDF file can be found in `source/main.pdf`.
