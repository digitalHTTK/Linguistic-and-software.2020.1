kurs: kurs.l kurs.y
		bison -d kurs.y
		flex kurs.l
		cc -o $@ kurs.tab.c lex.yy.c -lfl