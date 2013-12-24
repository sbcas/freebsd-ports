# $FreeBSD$

PORTNAME=	Rex
PORTVERSION=	0.43.7
CATEGORIES=	sysutils perl5
MASTER_SITES=	CPAN
MASTER_SITE_SUBDIR=	CPAN:JFRIED
PKGNAMEPREFIX=	p5-

MAINTAINER=	sam@cassiba.com
COMMENT=	Perl framework for automation and systems administration

LICENSE=	AL2

RUN_DEPENDS=	\
	p5-Net-SSH2>0:${PORTSDIR}/net/p5-Net-SSH2 \
	p5-Expect>0:${PORTSDIR}/lang/p5-Expect \
	p5-DBI>0:${PORTSDIR}/databases/p5-DBI
BUILD_DEPENDS:=	${RUN_DEPENDS}

USES=	perl5
USE_PERL5=	configure

.include <bsd.port.mk>
