lib_LTLIBRARIES = libnsspem.la

libnsspem_la_SOURCES = \
    anchor.c \
    ckpemver.c \
    constants.c \
    pargs.c \
    pfind.c \
    pinst.c \
    pobject.c \
    prsa.c \
    psession.c \
    pslot.c \
    ptoken.c \
    rsawrapr.c \
    util.c

include_HEADERS = \
    ckpem.h \
    nsspem.h

libnsspem_la_LDFLAGS= \
    -lnssckfw \
    -lnssb \
    -lfreebl \
    -Wl,--version-script,$(srcdir)/nsspem.def \
    -version-info 1:3:0

