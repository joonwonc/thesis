all:
	xelatex --shell-escape main.tex
	bibtex main
	xelatex --shell-escape main.tex
	xelatex --shell-escape main.tex

clean:
	rm -rf *.aux *.bbl *.blg *.log *.out
	rm -rf main.pdf
