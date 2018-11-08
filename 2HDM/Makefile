FILENAMES=$(basename $(wildcard *tex))

all: $(FILENAMES)

$(FILENAMES):
	pdflatex $@.tex
	command rm -f *.aux *.log *.nav *.out *.snm *.toc 
