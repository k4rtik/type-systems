all: ott pdf

ott: CbV_CbN.ott
	ott CbV_CbN.ott -o CbV_CbN.tex

pdf: CbV_CbN.tex
	texfot pdflatex CbV_CbN.tex

clean:
	rm -f *.tex *.aux *.pdf *.log
