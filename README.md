# pub-utils

A collection of utilities for managing LaTeX publications

### Contents

- [`check-macros`](./check-macros) - a program that checks for unused macros and environments in `.tex` files
- [`fix-bib`](./fix-bib) - a program that organizes `.bib` files
- [`mk-sub`](./mk-sub) - a program that creates the submission archive for a publication
- [`deweasel`](./deweasel) - a program that checks for "weasel words" from a list file
- [`derat`](./derat) - a program that checks for suspicious punctuation
- [`spellcheck`](./spellcheck) - a simple wrapper around `aspell`

### Dependencies
- [`bibtex-parser`](https://github.com/sciunto-org/python-bibtexparser) - for parsing `.bib` files
- [`habanero`](https://github.com/sckott/habanero) - for looking up citation information
- [`pylatexec`](https://github.com/phfaist/pylatexenc) - for parsing `.tex` files
- [`unidecode`](https://github.com/avian2/unidecode) - for handling special characters `.bib` files
- [`aspell`](https://github.com/GNUAspell/aspell) - for spellchecking

_see [`requirements.txt`](./requirements.txt) for version details_