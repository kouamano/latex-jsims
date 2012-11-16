all: toukou_card_v03.dvi toukou_card_v03.ps toukou_card_v03.pdf

toukou_card_v03.dvi: toukou_card_v03.tex
	platex toukou_card_v03.tex
	platex toukou_card_v03.tex

toukou_card_v03.ps: toukou_card_v03.dvi
	pdvips -D600 -P pdf -f toukou_card_v03.dvi > toukou_card_v03.ps

toukou_card_v03.pdf: toukou_card_v03.ps
	ps2pdf toukou_card_v03.ps
