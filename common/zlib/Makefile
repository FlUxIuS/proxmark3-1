MYSRCPATHS = ../../common/zlib
MYSRCS     = deflate.c adler32.c trees.c zutil.c inflate.c inffast.c inftrees.c
MYINCLUDES = -I../../common/zlib
MYCFLAGS   = -Wno-strict-prototypes -Wno-missing-prototypes -Wno-missing-declarations -Wno-old-style-definition -Wno-implicit-fallthrough
MYDEFS     = -DZ_SOLO -DNO_GZIP -DZLIB_PM3_TUNED
#-DDEBUG -Dverbose=1

LIB_A = libz.a

include ../../Makefile.host
