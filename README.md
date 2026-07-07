# Project structure 
All the projects within the repo follow the same structure, shown below,
which follows from the use of the `subfile` package.
```
    root/
      |- extra/
      |- src/
```
Here `extra` stores mainly a `preamble.tex` (project specific commands, acronyms, etc.),
and `BibTeX/` which stores the bibliography used within the project;
`src` on the other hand is the core part of each project as it stores all `tex`
files used, cleanly divided across sections (the `simple` directory), 
subsections (`sub`) and subsubsection (`subsub`). 
A `TikZ` directory is used to store all figures, table, listings, etc.

> [!Note]
> Each project uses a custom [class](https://github.com/UtsuroNoArashi/lectures2).

> [!Warning]
> The projects are compiled using lualatex, as it is needed by the class to use some TikZ libraries.
