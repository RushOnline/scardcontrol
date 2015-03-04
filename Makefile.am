# Process this file with automake to create Makefile.in.

noinst_PROGRAMS = scardcontrol
scardcontrol_SOURCES = scardcontrol.c PCSCv2part10.c PCSCv2part10.h
scardcontrol_CFLAGS = $(PCSC_CFLAGS) $(PTHREAD_CFLAGS)
scardcontrol_LDADD = $(PCSC_LIBS) $(PTHREAD_LIBS)

EXTRA_DIST = GPL-2

DISTCLEANFILES = \
	config.log \
	config.status

MAINTAINERCLEANFILES = \
	$(top_srcdir)/Makefile.in \
	$(top_srcdir)/aclocal.m4 \
	$(top_srcdir)/compile \
	$(top_srcdir)/configure \
	$(top_srcdir)/depcomp \
	$(top_srcdir)/install-sh \
	$(top_srcdir)/missing
