# Thesis
My thesis, written in TeX.

## Compiling
Run the following command from command line, or configure you TeX editor to compile with it:

Windows
```bash
pdflatex.exe -synctex=1 -interaction=nonstopmode -shell-escape %.tex
```

Linux & MacOS
```bash
pdflatex -synctex=1 -interaction=nonstopmode -shell-escape %.tex
```

## Dependencies
The `minted` package was used for code highlighting. This package depends on
`pygments`, which you will have to install via python.

- [Python 3.8 or above](https://www.python.org/downloads/)
- Python modules:
  - pygments
