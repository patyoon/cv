# About

My Curriculum Vitae in Latex. Source files from CV of [Adrien Friggeri](https://github.com/afriggeri/).

# Prerequisite (OS X)

1. Install [Basic TeX](http://www.tug.org/mactex/morepackages.html) and then run following to install packages.

2. Set `PATH`

```bash
PATH=/usr/local/texlive/2025basic/bin/universal-darwin:$PATH; export PATH
```

3. Install packages

```
sudo tlmgr update --self
sudo tlmgr install unicode-math textpos ucharcat filehook biblatex logreq xstring lm-math
```

# Compilation

```
xelatex cv.tex
```

Last updated 2026/02/23.
