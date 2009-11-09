# $OpenBSD:

COMMENT = Structured Type Constraints for Moose

MODULES =	cpan
DISTNAME = MooseX-Types-Structured-0.19
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS =  ::devel/p5-MooseX-Types \
	::devel/p5-Devel-PartialDump

REGRESS_DEPENDS = ::devel/p5-Test-Exception \

.include <bsd.port.mk>
