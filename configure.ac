AC_INIT([nss-pem], [1.0], [kdudka@redhat.com],
        [libnsspem], [https://github.com/kdudka/nss-pem])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_CONFIG_MACRO_DIRS([m4])
AC_PROG_CC
AM_PROG_AR
LT_INIT
AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([
    Makefile
    src/Makefile
])
AC_CHECK_LIB(nssb, NSSArena_Create)
AC_OUTPUT
