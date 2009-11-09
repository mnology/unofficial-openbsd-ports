# $OpenBSD:

COMMENT = Perl6 like method signature parser

MODULES =	cpan
DISTNAME = Parse-Method-Signatures-1.003012
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS = ::devel/p5-MooseX-Types \
	::devel/p5-PPI \
  ::devel/p5-MooseX-Types-Structured \
	::devel/p5-aliased \
	::devel/p5-MooseX-Traits \
 
REGRESS_DEPENDS =  ::devel/p5-Test-use-ok \
	::devel/p5-Test-Differences

.include <bsd.port.mk>
