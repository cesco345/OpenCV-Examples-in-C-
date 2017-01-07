# Include your C preprocessor flags
AM_CPPFLAGS = -I$(top_srcdir)/src

# Include the name of your binary
bin_PROGRAMS = executable

executable_SOURCES = \
  src/displayImage.cpp

#Include your cflags
 executable_CPPFLAGS= -I$(top_srcdir)
 executable_CXXFLAGS= $(OPENCV_CFLAGS) 
 executable_LDADD= $(OPENCV_LIBS)



