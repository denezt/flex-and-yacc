
FIND = find . -type f -name
FFLG = -delete

all: clean
	lex example.l
	cc lex.yy.c -o example -ll

clean:
	$(FIND) lex.yy.c $(FFLG)
	$(FIND) example $(FFLG)
