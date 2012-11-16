all: jsims-article-template.dvi jsims-article-template.ps jsims-article-template.pdf

jsims-article-template.dvi: jsims-article-template.tex fig-snapshot.tex fig-1-B.eps jsimsarticle.cls Table-youhou.tex
	platex jsims-article-template.tex
	platex jsims-article-template.tex

jsims-article-template.ps: jsims-article-template.dvi
	pdvips -f jsims-article-template.dvi > jsims-article-template.ps

jsims-article-template.pdf: jsims-article-template.ps
	ps2pdf13 jsims-article-template.ps
