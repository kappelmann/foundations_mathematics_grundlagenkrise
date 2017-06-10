TARGET=Presentation_Foundations_Mathematics_Foundational_Crisis

.PHONY: all clean watch

OPTIONS=-bibtex -pdf -pdflatex="pdflatex --shell-escape"

all:
	latexmk $(OPTIONS) $(TARGET).tex

clean:
	rm -rf *.aux *.bbl *.blg *.fdb_latexmk *.fls *.lof *.log *.lot *.out *.gnuplot *.table *.toc
