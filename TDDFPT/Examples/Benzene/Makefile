include ../make.inc

NAME = Benzene

default : all

all : check_results

check_results: $(NAME).pw-out $(NAME).tddfpt-out $(NAME).tddfpt_pp-out

clean :
	- /bin/rm -rf $(NAME).pw-out $(NAME).tddfpt-out $(NAME).tddfpt_pp-out *.plot_chi.dat out/*
