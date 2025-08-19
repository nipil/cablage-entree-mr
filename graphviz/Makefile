.PHONY: all

DEF = general.dot portail.dot interphone.dot
SVG = $(DEF:.dot=.svg)

all : $(SVG)

%.svg : %.dot
	dot -T svg -o ../images/$@ $<
