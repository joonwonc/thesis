all:
	xelatex --shell-escape main.tex
	bibtex main
	xelatex --shell-escape main.tex
	xelatex --shell-escape main.tex
	cp main.pdf ../pdf/thesis.pdf

clean:
	rm -rf *.aux *.bbl *.blg *.log *.out *.lof *.lot *.toc
	rm -rf main.pdf
