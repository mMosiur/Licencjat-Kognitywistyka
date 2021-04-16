# Głębokie uczenie maszynowe a neuronauka

[![build](https://github.com/mMosiur/Licencjat-Kognitywistyka/actions/workflows/build.yml/badge.svg)](https://github.com/mMosiur/Licencjat-Kognitywistyka/actions/workflows/build.yml)

Kod źródłowy pracy licencjackiej z kierunku Kognitywistyka na Uniwersytecie Marii Curie-Skłodowskiej w Lublinie.

Autor: Mateusz Piotr Moruś

Praca pisana pod przewodnictwem [dr hab. Grzegorza Wójcika](https://gmwojcik.pl/).

## Kompilacja

Wymagany `texlive` wraz z narzędziem do kompilacji `latexmk`

``` bash
cd Source
latexmk -synctex=1 -interaction=nonstopmode -file-line-error -pdf -outdir=out thesis.tex
cp out/thesis.pdf "../Głębokie uczenie maszynowe a neuronauka.pdf"
```
