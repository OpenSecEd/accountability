.PHONY: all
all: slides.pdf README.md

SRC=		contents.tex book-keeping.bib
FIGURES=	seclog.png

slides.pdf: slides.tex ${SRC} ${FIGURES}


README.md: video.md abstract.md
	${CAT} $^ > $@

TEX2MDFLAGS= 	-s --bibliography bibliography.bib -t markdown_strict

.INTERMEDIATE: abstract.md

abstract.md: abstract.tex
	${CONVERT.tex.md}


.PHONY: clean
clean:
	${RM} slides.pdf
	${RM} abstract.md


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
include ${INCLUDE_MAKEFILES}/doc.mk
