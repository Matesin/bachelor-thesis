.PHONY: pdf
pdf:
	@echo "running OpTeX on index.tex ..."
	optex main.tex

.PHONY: open
open: pdf
	@echo "opening PDF build ..."
	open main.pdf

.PHONY: copy
copy: pdf
	@echo "copying PDF build to the final destination ..."
	cp main.pdf ../thesis_draft.pdf

.PHONY: clean
clean:
	rm -rf main.log main.pdf main.ref texput.log
