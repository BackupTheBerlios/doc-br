#
# $FreeBSD: doc/en_US.ISO8859-1/articles/contributors/Makefile,v 1.11 2008/08/16 22:21:38 pgj Exp $
#
# Article: Contributors to FreeBSD

DOC?= article

FORMATS?= html
WITH_ARTICLE_TOC?= YES

INSTALL_COMPRESSED?=gz
INSTALL_ONLY_COMPRESSED?=

SRCS=	article.sgml
SRCS+=	contrib.ent
SRCS+=	contrib.386bsd.sgml
SRCS+=	contrib.additional.sgml
SRCS+=	contrib.committers.sgml
SRCS+=	contrib.corealumni.sgml
SRCS+=	contrib.develalumni.sgml

URL_RELPREFIX?=	../../../..
DOC_PREFIX?=	${.CURDIR}/../../..

.include "${DOC_PREFIX}/share/mk/doc.project.mk"
