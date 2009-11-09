# $OpenBSD:

COMMENT = Declarative syntax for Moose

MODULES =	cpan
DISTNAME = MooseX-Declare-0.32
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS = ::devel/p5-namespace-autoclean \
	::devel/p5-MooseX-Method-Signatures \
	::devel/p5-MooseX-Role-Paramterized

REGRESS_DEPENDS = ::devel/p5-Test-Exception \
	::devel/p5-Test-NoWarnings 

.include <bsd.port.mk>
