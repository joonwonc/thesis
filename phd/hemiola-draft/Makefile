.PHONY: all clean

INPUTNAME=hemiola
BUILD=./build

# all:
# 	pdflatex -output-directory $(BUILD) hemiola.tex
# 	bibtex hemiola
# 	pdflatex -output-directory $(BUILD) hemiola.tex
# 	pdflatex -output-directory $(BUILD) hemiola.tex

# clean:
# 	rm -rf $(BUILD)

all:
	latexmk -pdf -output-directory=$(BUILD) $(INPUTNAME).tex

clean:
	rm -rf $(BUILD)
