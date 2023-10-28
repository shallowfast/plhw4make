AUTOMAKE_OPTIONS = foreign
bin_PROGRAMS = somename
somename_SOURCES = main.c func.c
include_HEADERS =  header.h

clean-all: clean-am $(bin_PROGRAMS)
	find . ! \( -name "*.c" -o -name "*.h" -o -name "*.ac" -o -name "*.am" -o -name "*.MD" \) -delete
	rm @includedir@/$(include_HEADERS)
	rm @bindir@/$(bin_PROGRAMS)