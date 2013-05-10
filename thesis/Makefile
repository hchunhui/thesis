TEXINPUTS=.:template:
export TEXINPUTS

all: clean main.pdf
main.pdf: 
	xelatex -no-pdf main.tex
	bibtex main
	xelatex -no-pdf main.tex
	xelatex main.tex
clean:
	rm -rf *.aux *.lof *.lot *.bbl *.blg *.thm *.toc *.out *.xdv *.log *.exa *~
	rm -rf main.pdf
