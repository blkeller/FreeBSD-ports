# Created by: David Naylor <dbn@FreeBSD.org>
# $FreeBSD$

PORTNAME=	lttng-ust
PORTVERSION=	2.4.1
CATEGORIES=	sysutils linux
MASTER_SITES=	EPEL/l

MAINTAINER=	emulation@FreeBSD.org
COMMENT=	Libraries to instrument and trace user applications (CentOS ${LINUX_DIST_VER})

DESCR=		${.CURDIR}/../${PORTNAME}/pkg-descr
DOCSDIR=	${PREFIX}/usr/share/doc/${PORTNAME}
RPMVERSION=	1.el6
USES=		linux:c6
USE_LDCONFIG=	yes
USE_LINUX=	userspace-rcu
USE_LINUX_RPM=	yes

OPTIONS_DEFINE=	DOCS

.include <bsd.port.mk>
