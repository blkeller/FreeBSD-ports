# $FreeBSD$

PORTNAME=	gitit
PORTVERSION=	0.12.2.1
PORTREVISION=	3
CATEGORIES=	www haskell

MAINTAINER=	haskell@FreeBSD.org
COMMENT=	Wiki using happstack, git or darcs, and pandoc

LICENSE=	GPLv2

USE_CABAL=	ConfigFile HStringTemplate HTTP SHA aeson base64-bytestring \
		blaze-html feed filestore happstack-server highlighting-kate \
		hoauth2 hslogger http-client-tls http-conduit json mtl \
		old-locale old-time pandoc pandoc-types random \
		recaptcha safe split syb tagsoup uri url utf8-string \
		uuid xml xss-sanitize zlib

EXECUTABLE=	expireGititCache gitit

IGNORE=		Doesn't build with newest packages
DEPRECATED=	Doesn't build with newest packages
EXPIRATION_DATE=	2018-10-22

FLAGS_DEFINE=	PLUGINS
FLAGS_DEFAULT=	PLUGINS

PLUGINS_DESC=		Enable support for plugins
PLUGINS_FLAG_ENABLE=	plugins
PLUGINS_FLAG_CABAL=	ghc-paths

FLAGS_ENABLE=		network-uri

.include "${.CURDIR}/../../lang/ghc/bsd.cabal.mk"
.include <bsd.port.mk>
