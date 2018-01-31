PDF = pdflatex

.PHONY: all view

all : sujet.pdf
	$(PDF) sujet.tex
	open sujet.pdf

view :
	open sujet.pdf

sujet.pdf : sujet.tex
	$(PDF) sujet.tex
