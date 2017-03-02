AM_CFLAGS = -I$(top_srcdir)/src `pkg-config --cflags xft pango pangoxft`
# Library
lib_LTLIBRARIES 	= libxosd.la
libxosd_la_SOURCES 	= xosd.c intern.h
libxosd_la_LIBADD 	= $(X_LIBS)
libxosd_la_LDFLAGS = -version-info $(LT_CURRENT):$(LT_REVISION):$(LT_AGE) -pthread

 
