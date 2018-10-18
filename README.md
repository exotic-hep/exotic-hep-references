# Bibliography of the Exotic High Enery Physics theory group at FIAS

This bibliopgrahy shall cover a number of papers referenced by a number of papers written by members of the
[Exotic HEP group](https://www.fias.science/en/theoretical-physics/research-groups/piero-nicolini/)
at [Frankfurt Institute for Advanced Studies](https://fias.institute/). It is **not** meant to be exhaustive.
This repository is an attemp to start with a structured bibtex file which can be extended for future
work.

## How to use this bibliography in papers

If you don't use [git](https://git-scm.com/) otherwise, go to the directory where you write the paper, type

    git clone https://github.com/exotic-hep/exotic-hep-references.git .

You can then just use and modify the bibliography as usual:

    pdflatex example.tex
    pdflatex example.tex
    bibtex example
    pdflatex example.tex

## Rules for modifying the bibtex file

* Never remove an entry. If you remove an entry, existing papers won't compile any more.
* Never remove fields from entries. Again, existing papers won't compile properly any more.
* Human-readable citation names are prefered over ADS or SPIRES conventions (i.e. `Einstein1905` is good)
* Outdated entries may be updated (adding new fields or informations)
* If an entry doesn't look nice, don't change the entry but change the bibtex style in your document.
  If you cannot live with an existing entry, duplicate it with a new name.
