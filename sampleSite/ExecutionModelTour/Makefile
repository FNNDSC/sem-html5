######################################
%.html: %.haml
	haml -f html5 $^ $@
######################################
HTML= index.html

######################################
all: ${HTML}

clean:
	rm -f ${HTML}
