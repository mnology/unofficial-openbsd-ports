# $OpenBSD:

COMMENT = Build a URI from a set of named parameters

MODULES 	= cpan
DISTNAME   	= URI-FromHash-0.03
CATEGORIES 	= www

MAINTAINER = Erik Johansen <lemnayde@mnology.com>

# Perl
PERMIT_PACKAGE_CDROM 	= Yes
PERMIT_PACKAGE_FTP 		= Yes
PERMIT_DISTFILES_CDROM 	= Yes
PERMIT_DISTFILES_FTP 	= Yes

BUILD_DEPENDS= ${RUN_DEPENDS}
RUN_DEPENDS= ::devel/p5-Params-Validate \
	::www/p5-URI

do-install:
	${INSTALL_DATA_DIR} ${PREFIX}/${P5SITE}/URI
	${INSTALL_DATA} ${WRKSRC}/lib/URI/FromHash.pm \
    	${PREFIX}/${P5SITE}/URI/
	${INSTALL_MAN_DIR} ${PREFIX}/man/man3p/
	${INSTALL_MAN} ${WRKSRC}/blib/libdoc/URI::FromHash.3p \
		${PREFIX}/man/man3p/

.include <bsd.port.mk>
