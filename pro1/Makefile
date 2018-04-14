latexfile = hw1

init:pdf

pdf:
	latex ${latexfile}.tex
	dvips ${latexfile}.dvi
	ps2pdf ${latexfile}.ps
	rm -f ${latexfile}.aux ${latexfile}.dvi ${latexfile}.log ${latexfile}.ps
