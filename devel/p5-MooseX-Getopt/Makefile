# $OpenBSD:

COMMENT = A Moose role for processing command line options

MODULES =	cpan
DISTNAME = MooseX-Getopt-0.25
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

REGRESS_DEPENDS = ::devel/p5-Test-Exception \
	::devel/p5-Moose

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS = ::devel/p5-Getopt-Long-Descriptive

.include <bsd.port.mk>
