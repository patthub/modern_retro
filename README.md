# Retrokonwersja PBL – przeglądarka wyników

Strona: https://patthub.github.io/modern_retro/

Rekordy bibliograficzne „Polskiej Bibliografii Literackiej” (1944–1988) z rozpoznanymi elementami opisu
(autor, czasopismo, numeracja, wydawnictwo, miejsce i data wydania, opis fizyczny…).

Dane w `data/` generuje `kod_programistyczny/strona/eksport.py` z repozytorium
[Metody-automatycznej-retrospektywnej-konwersji-bibliografii](https://github.com/patthub/Metody-automatycznej-retrospektywnej-konwersji-bibliografii)
z plików CSV zwracanych przez `apply_ner_to_dataframe`:

    python eksport.py wyniki/*.csv   # zapisuje data/<rocznik>.json i data/index.json

Obecne dane: podejście hybrydowe (model spaCy + reguły).
