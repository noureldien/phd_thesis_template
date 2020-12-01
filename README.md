# PhD Thesis Template - Tips & Tricks
- If you prefer to import from overleaf.com, here is the [public link](https://www.overleaf.com/read/dhjssjhhymmr)
- Your starting point is `thesis.tex`
- You can customize the style in `styles.tex`
- All imported packages is in `packages.tex`
- Add your bibliography in `thesis.bib`
- Add the content of each chapter in a separate folder. See folder `chapter_1` as an example.
- Add the figures of each chapter in its designated folder, e.g. `figures/chapter_0`.
- Add this header `%!TEX root = thesis.tex` as the first line of every `.tex` file you use. This tells the latex compiler which `.tex` file is the root file.
- You can follow the following convention for the labels of tables/figures/equations in your paper before importing it as a chapter in the thesis. This way, you can avoid name collision of labels. 
    + For tables, use: `\label{ch2:fig:3-1}`
    + For figures, use: `\label{ch2:fig:2-4}`
    + For equations, use: `\label{ch2:eqn:1-2}`
    + Notice, ch2 is a prefix to refer to the chapter.
    + While `fig/tbl/eqn` refer to the type of the label.
    + Finally, the `1-2` refers to the second figure in the first section of the chapter.