# Created by: Ed Schouten <ed@FreeBSD.org>
# $FreeBSD$

PKGNAMEPREFIX=	cloudabi-
PKGNAMESUFFIX=	-x86_64

MAINTAINER=	ed@FreeBSD.org
COMMENT=	GNU Binutils for CloudABI cross-development

MASTERDIR=	${.CURDIR}/../binutils
PATCHDIR=	${.CURDIR}/files
PLIST=		${.CURDIR}/pkg-plist

BUTARGET=	x86_64-unknown-cloudabi
BUREMOVE=	ar dlltool ld ld.bfd nlmconv nm objdump ranlib size windmc \
		windres

.include "${MASTERDIR}/Makefile"
