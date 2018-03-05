AC_PREREQ(2.61)
AC_INIT(net, 0.1, https://github.com/troglobit/net/issues)
AM_INIT_AUTOMAKE([1.11 foreign dist-xz])
AM_SILENT_RULES([yes])

AC_CONFIG_SRCDIR([net.c])
AC_CONFIG_HEADER([config.h])
AC_CONFIG_FILES([Makefile])

# Define necessary build flags
AC_GNU_SOURCE
AC_USE_SYSTEM_EXTENSIONS

# Check for required packages
PKG_PROG_PKG_CONFIG
PKG_CHECK_MODULES([libnl], [libnl-3.0 >= 3.2.0])

AC_OUTPUT
