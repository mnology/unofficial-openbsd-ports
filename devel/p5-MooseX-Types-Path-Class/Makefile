# $OpenBSD:

COMMENT = A Path::Class type library for Moose

MODULES 	= cpan
DISTNAME 	= MooseX-Types-Path-Class-0.05
CATEGORIES 	= devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

BUILD_DEPENDS= ${RUN_DEPENDS}
RUN_DEPENDS= ::devel/p5-Class-MOP \
	::devel/p5-MooseX-Types \
	::devel/p5-Path-Class

.include <bsd.port.mk>
