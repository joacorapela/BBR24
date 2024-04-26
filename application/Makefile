all: application.pdf

%.pdf: %.tex
	pdflatex $<
	bibtex $*.aux
	pdflatex $<
	pdflatex $<

application.pdf: application.tex summary.tex coreTeam.tex vision.tex approach.tex resourceFig.tex
