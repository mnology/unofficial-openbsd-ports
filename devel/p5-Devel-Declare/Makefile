# $OpenBSD:

COMMENT =	Adding keywords to perl, in perl

MODULES =	cpan
DISTNAME = Devel-Declare-0.005011
CATEGORIES =	devel

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

BUILD_DEPENDS= ${RUN_DEPENDS}
RUN_DEPENDS= ::devel/p5-B-Hooks-EndOfScope \
	::devel/p5-B-Hooks-OP-Check
	::devel/p5-Sub-name
	
.include <bsd.port.mk>
