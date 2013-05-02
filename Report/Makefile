FIL=report

all: report.tex bibliography.bib
	bibtex ${FIL}
	pdflatex ${FIL}
	pdflatex ${FIL}
	pdflatex ${FIL}

pdf: report.tex bibliography.bib
	bibtex ${FIL}
	pdflatex ${FIL}
	pdflatex ${FIL}
	pdflatex ${FIL}
	rm report.aux report.blg report.bbl report.toc report.log report.out
	rm sections/*.aux

clean:
	rm report.aux report.blg report.bbl report.toc report.log report.out
	rm sections/*.aux
