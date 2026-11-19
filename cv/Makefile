.PHONY: all en zh

all: $(if $(wildcard main.tex),en) $(if $(wildcard main_zh.tex),zh)

en:
	latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex

zh:
	latexmk -lualatex -interaction=nonstopmode -halt-on-error main_zh.tex
