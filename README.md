# About
A collection of notes written in LaTeX during my master in CS.

## Projects structure
To allow a better management of each project, 
    we choosed to use the `subfiles` package, as allows files as these are part of a module.
    Additionaly, to keep things structured, each project is built using the same broad structure shown below.   
```
    root/
      |-extra/
      |-src/
        |-sections/
        |-main.tex 
        |-main.pdf
```
> [!Note]
> The projects use a custom class. See [lectures2](https://github.com/UtsuroNoArashi/lectures2) for more.

Here by `root` we mean the name of each project; `extra`, when present,
    stores files such as images, data sets, bibliographic entries, etc. 
    The `sections` directory stores the content of each `section`, `subsection`, `subsubsection` 
    and `TikZ` like files, each in its own directory.

## About the bibliography 
Although we don't provide papers, books or such directly, 
    if found, we try to provide the `DOI`.
