TEXINPUTS=.:template:
export TEXINPUTS
LAFLAGS=-interaction=nonstopmode

all: clean main.pdf
main.pdf: 
	xelatex -no-pdf $(LAFLAGS) main.tex
	bibtex main
	xelatex -no-pdf $(LAFLAGS) main.tex
	xelatex $(LAFLAGS) main.tex
clean:
	rm -rf *.aux *.lof *.lot *.bbl *.blg *.thm *.toc *.out *.xdv *.log *.exa *~
	rm -rf main.pdf
