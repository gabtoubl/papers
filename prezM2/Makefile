NAME		=prezM2Gabtoubl

all:		$(NAME).tex
		xelatex $(NAME).tex
		bibtex $(NAME)
		xelatex $(NAME).tex
		xelatex $(NAME).tex

clean:
		@rm -vf $(NAME).aux $(NAME).bbl $(NAME).blg $(NAME).log $(NAME).toc

fclean:	clean
		@rm -vf $(NAME).pdf
