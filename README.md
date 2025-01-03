# Kompilierung mit XeLaTeX & Biber

Ich kompiliere mit der IDE, aber die macht vermutlich auch nur das hier:
```bash
bash> xelatex --shell-escape -output-directory=out src/main.tex
bash> biber --output-directory out out/main
bash> xelatex --shell-escape -output-directory=out src/main.tex
bash> xelatex --shell-escape -output-directory=out src/main.tex
```