NULL =

INCLUDES =				\
	-I$(top_srcdir)/libmenu-cache	\
	-DGMENU_I_KNOW_THIS_IS_UNSTABLE	\
	$(GLIB_CFLAGS)			\
	$(MONITOR_CFLAGS)		\
	$(DEBUG_CFLAGS)			\
	$(WARN_CFLAGS)			\
    $(ADDITIONAL_FLAGS) \
	-Werror-implicit-function-declaration \
	$(NULL)

pkglibexec_PROGRAMS = menu-cache-gen

menu_cache_gen_SOURCES =		\
	menu-cache-gen.c		\
	menu-cache-gen.h		\
	canonicalize.c			\
	canonicalize.h			\
	desktop-entries.c		\
	desktop-entries.h		\
	entry-directories.c		\
	entry-directories.h		\
	gmenu-tree.c			\
	gmenu-tree.h			\
	menu-layout.c			\
	menu-layout.h			\
	menu-monitor.c			\
	menu-monitor.h			\
	menu-util.c			\
	menu-util.h			\
	$(NULL)

menu_cache_gen_LDADD = 		\
	$(GLIB_LIBS)					\
	$(MONITOR_LIBS)					\
	$(NULL)
menu_cache_gen_LDFLAGS =			\
	-no-undefined				\
	$(NULL)
EXTRA_DIST =				\
	$(NULL)
