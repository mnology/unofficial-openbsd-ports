# $OpenBSD:

COMMENT = Method declarations with type constraints and no source filter

MODULES =	cpan
DISTNAME = MooseX-Method-Signatures-0.29
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS = ::devel/p5-MooseX-Types \
	::devel/p5-Parse-Method-Signatures \
	::devel/p5-MooseX-Meta-TypeConstraint-ForceCoercion
	::devel/p5-Context-Preserve \
	::devel/p5-MooseX-LazyRequire \
	::devel/p5-Declare-Declare

.include <bsd.port.mk>
