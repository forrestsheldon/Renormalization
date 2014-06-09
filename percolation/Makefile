docname=percolation

all:
	pdflatex ${docname}.tex
	pdflatex ${docname}.tex
	bibtex ${docname}
	pdflatex ${docname}.tex

clean:
	rm ${docname}.aux
	rm ${docname}.log
	rm ${docname}.pdf
