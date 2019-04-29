.PHONY: all
all: slides.pdf

SRC=		contents.tex book-keeping.bib
FIGURES=	seclog.png

slides.pdf: slides.tex ${SRC} ${FIGURES}


.PHONY: clean
clean:
	${RM} slides.pdf


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
