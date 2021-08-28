TARGET = DPJ
all: ott pdf

ott: $(TARGET).ott
	ott $(TARGET).ott -o $(TARGET).tex

pdf: $(TARGET).tex
	texfot pdflatex $(TARGET).tex

clean:
	rm -f *.tex *.aux *.pdf *.log
