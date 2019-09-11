%.png : %.svg
	convert -density 72 $< $@
	#cairosvg  $< -o $@

svgfiles:=$(wildcard *.svg)
pngfiles=$(svgfiles:.svg=.png)

default : $(pngfiles)

clean :
	$(RM) *.png
