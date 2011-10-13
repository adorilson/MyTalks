all: clean apostila.tex
	pdflatex apostila
	bibtex apostila
	pdflatex apostila
	pdflatex apostila
	evince apostila.pdf&

apre: clean apresentacao.tex
	pdflatex apresentacao.tex
	pdflatex apresentacao.tex
	evince apresentacao.pdf&

clean:
	@rm -f *.pdf *.aux *.toc *.l* *.snm *.out *.nav *.bb* *.bl*
