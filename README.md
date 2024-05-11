# Revealjs template

The theme for this slide was inspired by the beamer template, [metropolis](https://ja.overleaf.com/latex/templates/metropolis-beamer-theme/qzyvdhrntfmr).

The github repository for metropolis is [here](https://github.com/matze/mtheme).

## How to use

1. Download the scss file or clone this repository.

2. In Quarto's YAML header, write the following:

```yaml
---
title: "Title"
author: "Author"
date: "Date"
insitute: "Institute"
format: 
    revealjs: 
      standalone: true
      theme: 
        - default
        - metropolis.scss
      slide-number: true
      date-format: long
---
```

3. Render the file with Quarto.

Note that the `metropolis.scss` file should be in the same directory as the `.qmd` file.

If there is no scss file in the same directory, specify it in a YAML header using a path relative to the qmd file.