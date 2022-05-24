# Initialization section
AC_INIT([Elephas], [1], [cris.svale@gmail.com])
AC_CONFIG_SRCDIR([src/main.c])
AM_INIT_AUTOMAKE([-Wall foreign])
AM_SILENT_RULES([yes])
# Shopping list section
AC_PROG_CC
PKG_PROG_PKG_CONFIG
PKG_CHECK_MODULES([ELEPHAS], [
    glib-2.0
    gtk4
])
AM_GNU_GETTEXT([external])
AM_GNU_GETTEXT_VERSION([0.21])
IT_PROG_INTLTOOL([0.51])
# Output section
AC_CONFIG_FILES([
    Makefile
    src/Makefile
    pixmaps/Makefile
    po/Makefile.in
])
AC_OUTPUT
# Variables
GETTEXT_PACKAGE=${PACKAGE_TARNAME}
AC_SUBST([GETTEXT_PACKAGE])

