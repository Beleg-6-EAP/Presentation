[![Build](https://github.com/Beleg-6-EAP/Presentation/actions/workflows/build-latex-push-pdf.yml/badge.svg)](https://github.com/Beleg-6-EAP/Presentation/actions/workflows/build-latex-push-pdf.yml)

# Präsentation Enterprise Architektur-Muster

Enterprise Architecture Patterns

Autoren: Julian Bruder, Abdellah Filali, Luca Franke

Modul “Software Engineering” (Prof. Dr. Andreas Both, Wintersemester 2024/2025) an der HTWK Leipzig

Das dazugehörige Repository des Papiers kann unter [Beleg-6-EAP/Belegarbeit](https://github.com/Beleg-6-EAP/Belegarbeit) gefunden werden.

## Build

```bash
bash> xelatex --shell-escape -output-directory=out src/main.tex
bash> biber --output-directory out out/main
bash> xelatex --shell-escape -output-directory=out src/main.tex
bash> xelatex --shell-escape -output-directory=out src/main.tex
```