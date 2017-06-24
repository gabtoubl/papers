NAME		=posterM2Gabtoubl

all:		$(NAME).tex biblio.bib
		xelatex $(NAME).tex
		bibtex  $(NAME)
		xelatex $(NAME).tex
		xelatex $(NAME).tex

clean:
		@rm -vf $(NAME).aux $(NAME).bbl $(NAME).blg $(NAME).log a0header.ps

fclean:		clean
		@rm -vf $(NAME).pdf
