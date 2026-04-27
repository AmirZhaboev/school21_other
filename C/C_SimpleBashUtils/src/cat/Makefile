FLAGS = -Wall -Wextra -Werror -pedantic -std=c11
all: s21_cat

s21_cat: Makefile s21_cat.c
	gcc $(FLAGS) s21_cat.c -o s21_cat

rebuild:
	clean all
	make all

clean:
	rm -f s21_cat
