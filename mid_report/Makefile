all: clean mid_short.pdf
mid_short.pdf: 
	xelatex -no-pdf mid_short.tex
	xelatex -no-pdf mid_short.tex
	xelatex mid_short.tex
clean:
	rm -rf *.aux *.lof *.lot *.bbl *.blg *.thm *.toc *.out *.xdv *.log *.exa *.snm *.nav *.vrb *~
	rm -rf mid_short.pdf
