# $OpenBSD$

COMMENT =		module that supports the Python WSGI interface

DISTNAME =		mod_wsgi-2.6
CATEGORIES =		www

HOMEPAGE =		http://code.google.com/p/modwsgi/
MASTER_SITES =		http://modwsgi.googlecode.com/files/

MAINTAINER =		Erik Johansen <lemnayde@mnology.com>

# Apache
PERMIT_PACKAGE_CDROM =	Yes
PERMIT_PACKAGE_FTP =	Yes
PERMIT_DISTFILES_CDROM =Yes
PERMIT_DISTFILES_FTP =	Yes

FLAVORS = apache2
FLAVOR ?=

APXS = /usr/sbin/apxs

.if ${FLAVOR:L:Mapache2}
APACHE_MODULE = www/apache-httpd
.else
APACHE_MODULE = apache-module
.endif

MODULES =		${APACHE_MODULE} \
			lang/python

MODAPACHE_NAME =	wsgi

CONFIGURE_STYLE =	gnu
CONFIGURE_ARGS +=	--with-python=${MODPY_BIN}

.if ${FLAVOR:L:Mapache2}
CONFIGURE_ARGS += --with-apxs=${APXS}
.endif

WANTLIB =		util
LIB_DEPENDS +=		${MODPY_LIB_DEPENDS}

NO_REGRESS =		Yes

do-build:
	(cd ${WRKBUILD}; ${APXS} -o mod_wsgi.so -c *.c)

post-build:
	@${MODAPACHE_CREATE_ENABLE_SCRIPT}

do-install:
	${MODAPACHE_INSTALL}

.include <bsd.port.mk>
