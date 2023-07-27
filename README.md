# pub-utils

A collection of utilities for managing LaTeX publications

### Contents

- [`check-macros`](./check-macros) - a program that checks for unused macros and environments in `.tex` files
- [`fix-bib`](./fix-bib) - a program that organizes `.bib` files
- [`mk-sub`](./mk-sub) - a program that creates the submission archive for a publication

### Dependencies
- [`bibtex-parser`](https://github.com/sciunto-org/python-bibtexparser) - for parsing `.bib` files
- [`habanero`](https://github.com/sckott/habanero) - for looking up citation information
- [`pylatexec`](https://github.com/phfaist/pylatexenc) - for parsing `.tex` files
- [`unidecode`](https://github.com/avian2/unidecode) - for handling special characters `.bib` files

_see [`requirements.txt`](./requirements.txt) for version details_