# Generated automatically from Makefile.in by configure.
# This is the Makefile for the examples subdirectory of readline. -*- text -*-
#
srcdir = .
VPATH = .:.
top_srcdir = ..
BUILD_DIR = .

DEFS = -DHAVE_CONFIG_H
CC = gcc
CFLAGS = -g -O
LOCAL_CFLAGS = 
CPPFLAGS = 

INCLUDES = -I $(srcdir) -I $(top_srcdir) -I..

CCFLAGS  = $(DEFS) $(LOCAL_CFLAGS) $(CPPFLAGS) $(INCLUDES) $(CFLAGS)
LDFLAGS = -g -L.. -Zexe

.c.o:
	$(CC) $(CCFLAGS) -c $<

EXECUTABLES = fileman rltest rl

all: $(EXECUTABLES)

rl: rl.o
	$(CC) $(LDFLAGS) -o $@ rl.o -lreadline -ltermcap

fileman: fileman.o
	$(CC) $(LDFLAGS) -o $@ fileman.o -lreadline -ltermcap

rltest: rltest.o
	$(CC) $(LDFLAGS) -o $@ rltest.o -lreadline -ltermcap

fileman.o: $(srcdir)/fileman.c
rltest.o: $(srcdir)/rltest.c
rl.o: $(srcdir)/rl.c
