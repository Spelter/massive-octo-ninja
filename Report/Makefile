FIL=report

all: report.tex bibliography.bib
	pdflatex ${FIL}
	bibtex ${FIL}
	pdflatex ${FIL}
	pdflatex ${FIL}

pdf: report.tex bibliography.bib
	pdflatex ${FIL}
	bibtex ${FIL}
	pdflatex ${FIL}
	pdflatex ${FIL}
	rm report.aux report.blg report.bbl report.toc report.log report.out report.lof
	rm sections/*.aux

clean:
	rm report.aux report.blg report.bbl report.toc report.log report.out report.lof
	rm sections/*.aux
