# Simple LaTeX Package
A LaTeX package cocktail for grad school level writings and presentations

## Description

It always annoys me when I start to write a new paper and I have use an old paper as a template. I don't want to remember all the packages. So I created this to streamline my writing process (a little bit). At first it was only for creating Beamer presentations with CRIS Lab (my graduate school lab) logos. But now it is general enough for other purposes.

## Compatible Document Classes

- IEEEtran
- Report
- Book
- Beamer (CRIS Lab logo)
- R markdown (CRIS Lab logo)

## How to Use the Templates?

- Choose a document class
    + IEEEtran
        * `journal_main.tex`: journal article template which uses the IEEEtran class
    + Report
        * `thesis_main.tex`: thesis main file **(missing)**
        * `thesis_header`: thesis header file
    + Book **(incomplete)**
    + Beamer
        * `cris_style.sty`
        * `cris.pdf`: CRIS Lab logo
        * `NewEngineeringBlack.pdf`: Columbia Engineering Logo 
    + R markdown
        * `rmd_template.tex`
        * `rmd_header.tex`: R markdown template
- Use generic article components
    + `abstract.tex`: abstract
    + `definitions.tex`: glossary, acronyms, and notation
    + `text.tex`: article body

## Versions

#### 0.19 (2017-06-07)

- Last version before I created this repository
