#
# CDDL HEADER START
#
# The contents of this file are subject to the terms of the
# Common Development and Distribution License (the "License").
# You may not use this file except in compliance with the License.
#
# You can obtain a copy of the license at usr/src/OPENSOLARIS.LICENSE
# or http://www.opensolaris.org/os/licensing.
# See the License for the specific language governing permissions
# and limitations under the License.
#
# When distributing Covered Code, include this CDDL HEADER in each
# file and include the License file at usr/src/OPENSOLARIS.LICENSE.
# If applicable, add the following below this CDDL HEADER, with the
# fields enclosed by brackets "[]" replaced with your own identifying
# information: Portions Copyright [yyyy] [name of copyright owner]
#
# CDDL HEADER END
#
#
# Copyright (c) 1998, 2010, Oracle and/or its affiliates. All rights reserved.
#
#ident	"%Z%%M%	%I%	%E% SMI"

LINK_OBJS_i386 = \
	misc_link_i386.o \
	lx_link_i386.o \
	xen_link.o

lx_link_i386.o lx_link_i386.po lx_link_i386.ln := CPPFLAGS += -I$(UTSBASE)/common/brand/lx

xen_link.o xen_link.ln xen_link.po := CPPFLAGS += -I$(UTSBASE)/i86xpv

include ../Makefile.com

