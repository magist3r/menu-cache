NULL =

INCLUDES =				\
	-I$(top_srcdir)/libmenu-cache	\
	$(GLIB_CFLAGS)			\
	$(MONITOR_CFLAGS)		\
	$(DEBUG_CFLAGS)			\
	$(WARN_CFLAGS)			\
	$(ADDITIONAL_FLAGS) \
	-DMENUCACHE_LIBEXECDIR="\"$(pkglibexecdir)\"" \
	-Werror-implicit-function-declaration \
	$(NULL)

pkglibexec_PROGRAMS = menu-cached

menu_cached_SOURCES =		\
	menu-cached.c			\
	$(NULL)

menu_cached_LDADD = 		\
	$(GLIB_LIBS)					\
	$(NULL)
menu_cached_LDFLAGS =			\
	-no-undefined				\
	$(NULL)
EXTRA_DIST =				\
	$(NULL)
