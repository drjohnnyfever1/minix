# $NetBSD: Makefile,v 1.1 2010/07/16 13:56:31 jmmv Exp $

NOMAN=		# defined

.include <bsd.own.mk>

.PATH: ${.CURDIR}/..
TESTSDIR=	${TESTSBASE}/lib/libposix/posix2

CFLAGS+=	-D_POSIX_SOURCE

TESTS_C=	t_rename

.include <bsd.test.mk>
