# $OpenBSD:

COMMENT = URI related types and coercions for Moose

MODULES =	cpan
DISTNAME =  MooseX-Types-URI-0.02
CATEGORIES =	www

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

BUILD_DEPENDS= ${RUN_DEPENDS}
RUN_DEPENDS= ::devel/p5-namespace-clean \
	p5-MooseX-Types-Path-Class \
	p5-URI \
	p5-URI-FromHash

.include <bsd.port.mk>
