default: pdf
wiki2beamer: FORCE
	python2 ./wiki2beamer git.wiki > git.tex
FORCE:
dvi: wiki2beamer
	latex git
pdf: wiki2beamer
	pdflatex git
clean:
	git clean -fx
