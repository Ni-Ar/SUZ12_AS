# Analysis reports

This folder contains the `R` analysis reports used to generate the publication figures.

Each figure and correspective supplementary figure is a separate analysis report.

All reports are `quarto` markdown documents (`.qmd`) rendered to `html` as:

```sh
cd ~/OneDrive\ -\ CRG\ -\ Centre\ de\ Regulacio\ Genomica/Suz12_AS_project/_Code
```

Move to each figure subfolder:

```sh
cd Fig1
```

Render with:
```sh
quarto render Main_Panels_Fig1.qmd --to html
```

# Note of interactive plots and tables

In some of the analysis html reports I made the plots interactive and inluded some searchable interactive tables made from the `R ` dataframes. These features are not rendered when using the htmlpreview service from GitHub and are not displayed online. To fix this download locally the html pages, they are all self-contained with embed resources.

