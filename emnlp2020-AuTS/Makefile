all: #need to run this twice
	pdflatex emnlp2020.tex
bib:
	bibtex emnlo2020.aux
clean: 
	rm -rf *.{aux,bbl,blg,out,log,gz,dvi}
# run all once, run bib once, then run QuickBuild on TexMaker twice. Then it will fix the PDF
