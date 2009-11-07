# $OpenBSD:

COMMENT =	Easily build XS extensions that depend on XS extensions

MODULES =	cpan
DISTNAME = B-Hooks-OP-Check-0.18
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS= :devel/p5-ExtUtils-Depends->=0.302:devel/p5-ExtUtils-Depends
BUILD_DEPENDS= ${RUN_DEPENDS}

.include <bsd.port.mk>
