SHELL = /bin/sh
MAIN = resume
TEXFILE = $(MAIN).tex
PDFLATEX = pdflatex

all: $(MAIN).pdf

$(MAIN).pdf: $(TEXFILE)
	$(PDFLATEX) $(TEXFILE)

allclean: clean
	rm -f $(MAIN).pdf

clean:
	rm -f $(MAIN).log $(MAIN).aux $(MAIN).out
