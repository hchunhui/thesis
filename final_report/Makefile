all: clean final.pdf
final.pdf: 
	xelatex -no-pdf final.tex
	xelatex -no-pdf final.tex
	xelatex final.tex
clean:
	rm -rf *.aux *.lof *.lot *.bbl *.blg *.thm *.toc *.out *.xdv *.log *.exa *.snm *.nav *.vrb *~
	rm -rf final.pdf
