# Programs.  Don't install testprog.
bin_PROGRAMS        = osd_cat
noinst_PROGRAMS     = testprog

osd_cat_SOURCES     = osd_cat.c
testprog_SOURCES    = testprog.c

osd_cat_LDADD       = libxosd/libxosd.la
testprog_LDADD      = libxosd/libxosd.la

osd_cat_CFLAGS      = @XFT_CFLAGS@ @PANGO_CFLAGS@ @PANGOXFT_CFLAGS@
testprog_CFLAGS     = @XFT_CFLAGS@ @PANGO_CFLAGS@ @PANGOXFT_CFLAGS@

osd_cat_LDADD       += @XFT_LIBS@ @PANGO_LIBS@ @PANGOXFT_LIBS@
testprog_LDADD      += @XFT_LIBS@ @PANGO_LIBS@ @PANGOXFT_LIBS@

include_HEADERS     = xosd.h

AM_CFLAGS           = ${GTK_CFLAGS}

SUBDIRS             = libxosd xmms_plugin bmp_plugin
