.PATH: ${SRCTOP}/sys/dev/hid

KMOD=	hidmap
SRCS=	hidmap.c
SRCS+=	opt_hid.h opt_kbd.h
SRCS+=	bus_if.h device_if.h

EXPORT_SYMS=	YES

.include <bsd.kmod.mk>
