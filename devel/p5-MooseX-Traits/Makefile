# $OpenBSD:

COMMENT = automatically apply roles at object creation time

MODULES =	cpan
DISTNAME = MooseX-Traits-0.07
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS =  :p5-Moose->=0.84:devel/p5-Moose \
	::devel/p5-namespace-autoclean \

REGRESS_DEPENDS = ::devel/p5-Test-use-ok

.include <bsd.port.mk>
