include $(top_srcdir)/Makefile.common

AM_CFLAGS += $(WARN_CFLAGS)
AM_CPPFLAGS += $(WARN_CPPFLAGS)
AM_CXXFLAGS += $(STD_CXXFLAGS) $(WARN_CXXFLAGS)

INCLUDES = -I$(srcdir)/.. -isystem $(top_srcdir)/contrib

noinst_LIBRARIES = libtext.a
noinst_HEADERS = \
	DistanceFieldFont.h \
	FontDescriptor.h \
	Font.h \
	TextSupport.h \
	TextureFont.h

libtext_a_SOURCES = \
	DistanceFieldFont.cpp \
	FontDescriptor.cpp \
	Font.cpp \
	TextSupport.cpp \
	TextureFont.cpp
