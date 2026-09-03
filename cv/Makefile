.PHONY: pdf clean

ENGINE ?= lualatex

pdf:
	$(ENGINE) -interaction=nonstopmode -halt-on-error cv.tex

clean:
	rm -f cv.aux cv.log cv.out cv.pdf
