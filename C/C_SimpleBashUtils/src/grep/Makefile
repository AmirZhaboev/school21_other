FLAGS = -Wall -Wextra -Werror -pedantic -std=c11
all: s21_grep 

s21_cat: Makefile s21_grep.c
	gcc $(FLAGS) s21_grep.c -o s21_grep

rebuild:
	clean all
	make all

clean:
	rm -f s21_grep