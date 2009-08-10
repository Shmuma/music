all: 01-in-may.pdf 02-folk-song.pdf

%.pdf: %.ly
	lilypond $< && rm -f *.ps

clean:
	-rm -f *.pdf *.ps

