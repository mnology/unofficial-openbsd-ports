# $OpenBSD:

COMMENT =	Keep imports out of your namespace

MODULES =	cpan
DISTNAME = namespace-autoclean-0.09
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS =	::devel/p5-namespace-clean \
	::devel/p5-Class-MOP

BUILD_DEPENDS =	${RUN_DEPENDS}

.include <bsd.port.mk>
