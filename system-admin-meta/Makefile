# New ports collection makefile for:	system-admin-meta
# Date created:				2012-10-06
# Whom:					Dachi Chang <femc7488@gmail.com>
#
# $FreeBSD$
#

PORTNAME=	system-admin-meta
PORTVERSION=	1.0
CATEGORIES=	arkports
MASTER_SITES=	# none
DISTFILES=	# none

MAINTAINER=	femc7488@gmail.com
COMMENT=	Awesome Rapid Kit system administration tool set

RUN_DEPENDS=	ark-portmaster-config>=0:${PORTSDIR}/arkports/portmaster-config \
		portmaster>=0:${PORTSDIR}/ports-mgmt/portmaster \
		sudo>=0:${PORTSDIR}/security/sudo

NO_WRKSUBDIR=	yes
NO_BUILD=	yes

do-install:
	${DO_NADA}

.include <bsd.port.mk>
