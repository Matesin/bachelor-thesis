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
	cp main.pdf ../LionKey_NFC_Support.pdf

.PHONY: clean
clean:
	rm -rf main.log main.pdf main.ref texput.log
