# PhD Thesis

This repository contains the $\LaTeX$ source code and build automation for my PhD thesis.

## Live View

The latest compiled PDF and progress tracker are available here:

**[thesis.wiederhold.dev](https://thesis.wiederhold.dev)**

## $\LaTeX$ document class

I use `ut-thesis`, documented [here](https://ctan.org/tex-archive/macros/latex/contrib/ut-thesis/) and with source code found [here](https://github.com/jessexknight/ut-thesis).

I also use my own custom style file found [here](https://github.com/tonamatos/tonas-latex), imported as a submodule.

## Automation
This project uses GitHub Actions to:
1. Compile `thesis.tex` into a PDF on every push.
2. Deploy the result to the `gh-pages` branch.