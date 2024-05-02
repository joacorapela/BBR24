all: resourceFig.png

resourceFig.png: resourceFigContainer.tex
	pdflatex -jobname=resourceFig resourceFigContainer.tex
	inkscape  -o resourceFig.png resourceFig.pdf
