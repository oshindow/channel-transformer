# **********************************************************
# Makefile for rfilter1 Directory
# **********************************************************
SHELL = /bin/sh
PREFIX=/home/wxt/espnet/tools/sctk
bindir = $(PREFIX)/bin
T=../test_suite
PERL=/slp/sware/Linux/bin/perl

all: acomp.pl

acomp.pl: 
	chmod +x acomp.pl

setTests:

check: all
	@echo "Testing acomp.pl"
	@echo "   No tests defined for acomp.pl"

install: all
	cp acomp.pl $(bindir)

clean:

distclean: clean
	rm -r *~ makefile
