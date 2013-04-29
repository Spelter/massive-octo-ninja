FIL=report

all: report.tex bibliography.bib
	pdflatex ${FIL}
	pdflatex ${FIL}
	bibtex ${FIL}
	pdflatex ${FIL}

clean:
	rm report.aux report.blg report.bbl report.toc report.log report.out
	rm sections/*.aux
