# $OpenBSD:

COMMENT =  run code after a subroutine call, preserving the context \
the subroutine would have seen if it were the last statement in the \
caller

MODULES =	cpan
DISTNAME =  Context-Preserve-0.01
CATEGORIES =	devel

# Perl
PERMIT_PACKAGE_CDROM =		Yes
PERMIT_PACKAGE_FTP =		Yes
PERMIT_DISTFILES_CDROM =	Yes
PERMIT_DISTFILES_FTP =		Yes

CPAN_AUTHOR = JROCKWAY

REGRESS_DEPENDS = ::devel/p5-Test-use-ok \
	::devel/p5-Test-Exception

.include <bsd.port.mk>
