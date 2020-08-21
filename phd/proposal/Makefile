.PHONY: all clean

INPUTNAME=proposal
BUILD=./build

all:
	latexmk -pdf -output-directory=$(BUILD) $(INPUTNAME).tex

clean:
	rm -rf $(BUILD)
