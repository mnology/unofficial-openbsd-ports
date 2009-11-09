# $OpenBSD:

COMMENT =	Required attributes which fail only when trying to use them

MODULES =	cpan
DISTNAME =  MooseX-LazyRequire-0.04
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

BUILD_DEPENDS= ${RUN_DEPENDS}
RUN_DEPENDS= ::devel/p5-MooseX-Types \
	::devel/p5-Moose

.include <bsd.port.mk>
