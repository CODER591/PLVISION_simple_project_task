AUTOMAKE_OPTIONS = foreign
#SUBDIRS = src

bin_PROGRAMS = SimpleMakeProject
SimpleMakeProject_SOURCES = \
                    src/functions.c \
                    src/functions.h \
                    src/main.c

TO_REMOVE_ON_CLEANUP =	\
	config.log \
	autom4te.cache \
	missing \
	aclocal.m4 \
	compile \
	depcomp \
	deps \
	src/.deps \
	src/.dirstamp \
	.dirstamp \
	configure \
	configure~ \
	install-sh \
	Makefile \
	Makefile.in \
	config.status

.PHONY: clean-all

clean-all: clean uninstall
	rm -rf $(TO_REMOVE_ON_CLEANUP)
