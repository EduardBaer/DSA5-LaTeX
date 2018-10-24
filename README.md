# DSA5-LaTeX

Einfache LaTeX Vorlagen für einen Heldenhintergrund (*hintergrund.tex*) und eine Sammlung von Regelauszügen (*sf.tex*). Die Vorlagen verwenden dabei die offiziellen DSA5 Schriftarten.

## Abhängigkeiten

### LaTeX

Auf den meisten Systemen kann man ein Texlive Meta Paket installieren.

### Schriftarten

Für Gentium gibt es auf den meisten Systemen ein offizielles Paket. Andalus bekommt man als TTF aus dem [Scriptorium Aventuris - Layout-Baukasten](https://www.ulisses-ebooks.de/product/197880/Scriptorium-Aventuris--LayoutBaukasten).

## PDF erzeugen

Mit den folgenden Befehlen lassen sich aus den LaTeX Dateien PDFs erzeugen.

```
latexmk -lualatex hintergrund.tex
latexmk -lualatex sf.tex
```
