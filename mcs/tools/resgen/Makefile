thisdir = tools/resgen
SUBDIRS =
include ../../build/rules.make

PROGRAM = resgen.exe

CLEAN_FILES = resgen.exe

LIB_REFS = System System.Xml System.Core

INSTALL_PROFILE := $(filter $(DEFAULT_PROFILE), $(PROFILE))
ifndef INSTALL_PROFILE
NO_INSTALL = yes
endif

include ../../build/executable.make
