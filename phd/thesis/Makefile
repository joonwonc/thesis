.PHONY: all clean

INPUTNAME=thesis
BUILD=./build

all:
	latexmk -pdf -output-directory=$(BUILD) $(INPUTNAME).tex

clean:
	rm -rf $(BUILD)
