# $OpenBSD:

COMMENT = Persistent lexical variable values for arbitrary calls.

MODULES =	cpan
DISTNAME = Lexical-Persistence-1.01
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

RUN_DEPENDS = ${BUILD_DEPENDS}
BUILD_DEPENDS = ::devel/p5-PadWalker \
	::devel/p5-Devel-LexAlias

.include <bsd.port.mk>
