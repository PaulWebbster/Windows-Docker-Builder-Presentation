latex = pdflatex
compile_effects = *.pdf *.toc *.nav *.out *.aux *.log *.snm

presentation.pdf: presentation.tex
	$(latex) $<
	$(latex) $<

.PHONY: clean
clean:
	rm -rf $(compile_effects) 
