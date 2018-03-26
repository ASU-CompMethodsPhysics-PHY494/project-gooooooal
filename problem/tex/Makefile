NAME  := project_2
LATEX := $(NAME).tex
PDF   := $(NAME).pdf


%.pdf: %.tex
	pdflatex -shell-escape $<
	bibtex $*
	pdflatex -shell-escape $<
	pdflatex -shell-escape $<

.phony: all see copy

all: $(PDF)

see: $(PDF)
	open -a preview $^

copy: $(PDF)
	cp $^ ..


