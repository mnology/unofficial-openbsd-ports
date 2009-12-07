# $OpenBSD:

COMMENT = a modern perl interactive shell

MODULES =	cpan
DISTNAME = Devel-REPL-1.003007
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS = ::devel/p5-MooseX-Object-Pluggable \
	::devel/p5-File-HomeDir \
	::devel/p5-namespace-clean \
	::devel/p5-MooseX-Getopt \
	::devel/p5-MooseX-AttributeHelpers

REGRESS_DEPENDS = ::devel/p5-Test-Exception \
	::devel/p5-Test-NoWarnings 

.include <bsd.port.mk>
