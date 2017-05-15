ACLOCAL_AMFLAGS = -I m4
AM_DEFAULT_SOURCE_EXT = .cpp
AM_CPPFLAGS = $(DYPLO_CFLAGS)
AM_LDFLAGS = $(DYPLO_LIBS) $(PTHREAD_CFLAGS) $(PTHREAD_LIBS)

bin_PROGRAMS = \
	myfirstdyploappsw \
	myfirstdyploapphw

myfirstdyploappsw_SOURCES= dyplodemoapp.cpp softwareprocesses.hpp
myfirstdyploapphw_SOURCES = dyplodemoapp.cpp softwareprocesses.hpp

myfirstdyploapphw_CPPFLAGS = $(DYPLO_CFLAGS) -DHAVE_HARDWARE

