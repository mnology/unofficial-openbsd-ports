# $OpenBSD:

COMMENT = Partial dumping of data structures, optimized for argument printing.

MODULES =	cpan
DISTNAME = Devel-PartialDump-0.12
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS =  ::devel/p5-namespace-clean \
	::devel/p5-Any-Moose

REGRESS_DEPENDS = ::devel/p5-Test-use-ok

.include <bsd.port.mk>
