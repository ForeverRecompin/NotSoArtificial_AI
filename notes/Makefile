all: getpdf

getpdf:
	pdflatex tex/ai_notes.tex
	mkdir -p doc
	mv ai_notes.pdf doc/
clean:
	rm *.log
	rm *.aux
	rm *.toc
	rm *.out
	rm *~
	rm *.toc
