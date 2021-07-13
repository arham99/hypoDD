FLAGS=-O

SUBS = sacio.o fft.o Complex.o
PROGRAM = sac_wfcc src_ss

all: $(PROGRAM)

$(PROGRAM): %:%.o $(SUBS)
	$(LINK.c) -o $@ $@.o $(SUBS) -lm

clean:
	rm -f *.o

