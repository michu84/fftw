# Makefile.in generated by automake 1.11.6 from Makefile.am.
# mpi/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011 Free Software
# Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.






am__make_dryrun = \
  { \
    am__dry=no; \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        echo 'am--echo: ; @echo "AM"  OK' | $(MAKE) -f - 2>/dev/null \
          | grep '^AM OK$$' >/dev/null || am__dry=yes;; \
      *) \
        for am__flg in $$MAKEFLAGS; do \
          case $$am__flg in \
            *=*|--*) ;; \
            *n*) am__dry=yes; break;; \
          esac; \
        done;; \
    esac; \
    test $$am__dry = yes; \
  }
pkgdatadir = $(datadir)/fftw
pkgincludedir = $(includedir)/fftw
pkglibdir = $(libdir)/fftw
pkglibexecdir = $(libexecdir)/fftw
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-unknown-linux-gnu
host_triplet = x86_64-unknown-linux-gnu
#noinst_PROGRAMS = mpi-bench$(EXEEXT)
subdir = mpi
DIST_COMMON = $(am__include_HEADERS_DIST) $(srcdir)/Makefile.am \
	$(srcdir)/Makefile.in
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/acx_mpi.m4 \
	$(top_srcdir)/m4/acx_pthread.m4 \
	$(top_srcdir)/m4/ax_cc_maxopt.m4 \
	$(top_srcdir)/m4/ax_check_compiler_flags.m4 \
	$(top_srcdir)/m4/ax_compiler_vendor.m4 \
	$(top_srcdir)/m4/ax_gcc_aligns_stack.m4 \
	$(top_srcdir)/m4/ax_gcc_version.m4 \
	$(top_srcdir)/m4/ax_openmp.m4 $(top_srcdir)/m4/libtool.m4 \
	$(top_srcdir)/m4/ltoptions.m4 $(top_srcdir)/m4/ltsugar.m4 \
	$(top_srcdir)/m4/ltversion.m4 $(top_srcdir)/m4/lt~obsolete.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(libdir)" "$(DESTDIR)$(includedir)" \
	"$(DESTDIR)$(includedir)"
LTLIBRARIES = $(lib_LTLIBRARIES)
libfftw3_mpi_la_DEPENDENCIES =  \
	../libfftw3.la
am__objects_1 = any-true.lo api.lo block.lo choose-radix.lo conf.lo \
	dtensor.lo rearrange.lo wisdom-api.lo f03-wrap.lo
am__objects_2 = transpose-alltoall.lo transpose-pairwise.lo \
	transpose-recurse.lo transpose-problem.lo transpose-solve.lo
am__objects_3 = dft-serial.lo dft-rank-geq2.lo \
	dft-rank-geq2-transposed.lo dft-rank1.lo dft-rank1-bigvec.lo \
	dft-problem.lo dft-solve.lo
am__objects_4 = rdft-serial.lo rdft-rank-geq2.lo \
	rdft-rank-geq2-transposed.lo rdft-rank1-bigvec.lo \
	rdft-problem.lo rdft-solve.lo
am__objects_5 = rdft2-serial.lo rdft2-rank-geq2.lo \
	rdft2-rank-geq2-transposed.lo rdft2-problem.lo rdft2-solve.lo
am_libfftw3_mpi_la_OBJECTS = $(am__objects_1) \
	$(am__objects_2) $(am__objects_3) $(am__objects_4) \
	$(am__objects_5)
libfftw3_mpi_la_OBJECTS =  \
	$(am_libfftw3_mpi_la_OBJECTS)
libfftw3_mpi_la_LINK = $(LIBTOOL) --tag=CC \
	$(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=link $(CCLD) \
	$(AM_CFLAGS) $(CFLAGS) $(libfftw3_mpi_la_LDFLAGS) \
	$(LDFLAGS) -o $@
#am_libfftw3_mpi_la_rpath = -rpath $(libdir)
PROGRAMS = $(noinst_PROGRAMS)
am_mpi_bench_OBJECTS = mpi_bench-mpi-bench.$(OBJEXT) \
	mpi_bench-fftw-bench.$(OBJEXT) mpi_bench-hook.$(OBJEXT)
mpi_bench_OBJECTS = $(am_mpi_bench_OBJECTS)
am__DEPENDENCIES_1 =
mpi_bench_DEPENDENCIES = libfftw3_mpi.la \
	$(LIBFFTWTHREADS) $(top_builddir)/libfftw3.la \
	$(top_builddir)/libbench2/libbench2.a $(am__DEPENDENCIES_1) \
	$(am__DEPENDENCIES_1)
mpi_bench_LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) \
	$(LIBTOOLFLAGS) --mode=link $(CCLD) $(mpi_bench_CFLAGS) \
	$(CFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
SOURCES = $(libfftw3_mpi_la_SOURCES) $(mpi_bench_SOURCES)
DIST_SOURCES = $(libfftw3_mpi_la_SOURCES) \
	$(mpi_bench_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__include_HEADERS_DIST = fftw3-mpi.h
HEADERS = $(include_HEADERS) $(nodist_include_HEADERS)
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/michu/pluggedin/fftw/fftw/missing --run aclocal-1.11
ALLOCA = 
ALTIVEC_CFLAGS = 
AMTAR = $${TAR-tar}
AR = ar
AS = as
AUTOCONF = ${SHELL} /home/michu/pluggedin/fftw/fftw/missing --run autoconf
AUTOHEADER = ${SHELL} /home/michu/pluggedin/fftw/fftw/missing --run autoheader
AUTOMAKE = ${SHELL} /home/michu/pluggedin/fftw/fftw/missing --run automake-1.11
AVX_CFLAGS = 
AWK = gawk
CC = 
CCDEPMODE = depmode=gcc3
CFLAGS = -g3 -gdwarf-2
CHECK_PL_OPTS = 
CPP = /usr/bin/gcc -std=gnu99 -E
CPPFLAGS = 
CYGPATH_W = echo
C_FFTW_R2R_KIND = C_INT32_T
C_MPI_FINT = 
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = dlltool
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
F77 = 
FFLAGS = 
FGREP = /bin/grep -F
FLIBS = 
GREP = /bin/grep
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LD = /usr/bin/ld -m elf_x86_64
LDFLAGS = 
LIBOBJS = 
LIBQUADMATH = 
LIBS = -lm 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
MAINT = #
MAKEINFO = ${SHELL} /home/michu/pluggedin/fftw/fftw/missing --run makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
MPICC = 
MPILIBS = 
MPIRUN = 
NEON_CFLAGS = 
NM = /usr/bin/nm -B
NMEDIT = 
OBJDUMP = objdump
OBJEXT = o
OCAMLBUILD = 
OPENMP_CFLAGS = 
OTOOL = 
OTOOL64 = 
PACKAGE = fftw
PACKAGE_BUGREPORT = fftw@fftw.org
PACKAGE_NAME = fftw
PACKAGE_STRING = fftw 3.3.3
PACKAGE_TARNAME = fftw
PACKAGE_URL = 
PACKAGE_VERSION = 3.3.3
PATH_SEPARATOR = :
POW_LIB = 
PRECISION = d
PREC_SUFFIX = 
PTHREAD_CC = 
PTHREAD_CFLAGS = 
PTHREAD_LIBS = 
RANLIB = ranlib
SED = /bin/sed
SET_MAKE = 
SHARED_VERSION_INFO = 6:2:3
SHELL = /bin/bash
SSE2_CFLAGS = 
STACK_ALIGN_CFLAGS = 
STRIP = strip
THREADLIBS = 
VERSION = 3.3.3
abs_builddir = /home/michu/pluggedin/fftw/fftw/mpi
abs_srcdir = /home/michu/pluggedin/fftw/fftw/mpi
abs_top_builddir = /home/michu/pluggedin/fftw/fftw
abs_top_srcdir = /home/michu/pluggedin/fftw/fftw
ac_ct_AR = ar
ac_ct_CC = /usr/bin/gcc
ac_ct_DUMPBIN = 
ac_ct_F77 = 
acx_pthread_config = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-unknown-linux-gnu
host_alias = 
host_cpu = x86_64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/michu/pluggedin/fftw/fftw/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
AM_CPPFLAGS = -I$(top_srcdir)/kernel -I$(top_srcdir)/dft	\
-I$(top_srcdir)/rdft -I$(top_srcdir)/api -I$(top_srcdir)/tests	\
-I$(top_srcdir)/libbench2

#lib_LTLIBRARIES = libfftw3_mpi.la
#include_HEADERS = fftw3-mpi.h
#nodist_include_HEADERS = fftw3-mpi.f03 fftw3l-mpi.f03
EXTRA_DIST = testsched.c f03api.sh f03-wrap.sh genf03-wrap.pl fftw3-mpi.f03.in fftw3l-mpi.f03.in
BUILT_SOURCES = fftw3-mpi.f03.in fftw3-mpi.f03 fftw3l-mpi.f03.in fftw3l-mpi.f03 f03-wrap.c
CLEANFILES = fftw3-mpi.f03 fftw3l-mpi.f03
TRANSPOSE_SRC = transpose-alltoall.c transpose-pairwise.c transpose-recurse.c transpose-problem.c transpose-solve.c mpi-transpose.h
DFT_SRC = dft-serial.c dft-rank-geq2.c dft-rank-geq2-transposed.c dft-rank1.c dft-rank1-bigvec.c dft-problem.c dft-solve.c mpi-dft.h
RDFT_SRC = rdft-serial.c rdft-rank-geq2.c rdft-rank-geq2-transposed.c rdft-rank1-bigvec.c rdft-problem.c rdft-solve.c mpi-rdft.h
RDFT2_SRC = rdft2-serial.c rdft2-rank-geq2.c rdft2-rank-geq2-transposed.c rdft2-problem.c rdft2-solve.c mpi-rdft2.h
SRC = any-true.c api.c block.c choose-radix.c conf.c dtensor.c fftw3-mpi.h ifftw-mpi.h rearrange.c wisdom-api.c f03-wrap.c
libfftw3_mpi_la_SOURCES = $(SRC) $(TRANSPOSE_SRC) $(DFT_SRC) $(RDFT_SRC) $(RDFT2_SRC)
libfftw3_mpi_la_LDFLAGS = -version-info 6:2:3
libfftw3_mpi_la_LIBADD = ../libfftw3.la 
#mpi_bench_CFLAGS = $(OPENMP_CFLAGS)
#mpi_bench_CFLAGS = $(PTHREAD_CFLAGS)
#LIBFFTWTHREADS = $(top_builddir)/threads/libfftw3_threads.la
#LIBFFTWTHREADS = $(top_builddir)/threads/libfftw3_omp.la
mpi_bench_SOURCES = mpi-bench.c $(top_srcdir)/tests/fftw-bench.c $(top_srcdir)/tests/hook.c
mpi_bench_LDADD = libfftw3_mpi.la $(LIBFFTWTHREADS) $(top_builddir)/libfftw3.la $(top_builddir)/libbench2/libbench2.a $(MPILIBS) $(THREADLIBS)
CHECK = $(top_srcdir)/tests/check.pl
NUMCHECK = 10
CHECKSIZE = 10000
CHECKOPTS = --verbose --random --maxsize=$(CHECKSIZE) -c=$(NUMCHECK) $(CHECK_PL_OPTS)
all: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu mpi/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu mpi/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-libLTLIBRARIES: $(lib_LTLIBRARIES)
	@$(NORMAL_INSTALL)
	@list='$(lib_LTLIBRARIES)'; test -n "$(libdir)" || list=; \
	list2=; for p in $$list; do \
	  if test -f $$p; then \
	    list2="$$list2 $$p"; \
	  else :; fi; \
	done; \
	test -z "$$list2" || { \
	  echo " $(MKDIR_P) '$(DESTDIR)$(libdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(libdir)" || exit 1; \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 '$(DESTDIR)$(libdir)'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL) $(INSTALL_STRIP_FLAG) $$list2 "$(DESTDIR)$(libdir)"; \
	}

uninstall-libLTLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@list='$(lib_LTLIBRARIES)'; test -n "$(libdir)" || list=; \
	for p in $$list; do \
	  $(am__strip_dir) \
	  echo " $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f '$(DESTDIR)$(libdir)/$$f'"; \
	  $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=uninstall rm -f "$(DESTDIR)$(libdir)/$$f"; \
	done

clean-libLTLIBRARIES:
	-test -z "$(lib_LTLIBRARIES)" || rm -f $(lib_LTLIBRARIES)
	@list='$(lib_LTLIBRARIES)'; for p in $$list; do \
	  dir="`echo $$p | sed -e 's|/[^/]*$$||'`"; \
	  test "$$dir" != "$$p" || dir=.; \
	  echo "rm -f \"$${dir}/so_locations\""; \
	  rm -f "$${dir}/so_locations"; \
	done
libfftw3_mpi.la: $(libfftw3_mpi_la_OBJECTS) $(libfftw3_mpi_la_DEPENDENCIES) $(EXTRA_libfftw3_mpi_la_DEPENDENCIES) 
	$(libfftw3_mpi_la_LINK) $(am_libfftw3_mpi_la_rpath) $(libfftw3_mpi_la_OBJECTS) $(libfftw3_mpi_la_LIBADD) $(LIBS)

clean-noinstPROGRAMS:
	@list='$(noinst_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list
mpi-bench$(EXEEXT): $(mpi_bench_OBJECTS) $(mpi_bench_DEPENDENCIES) $(EXTRA_mpi_bench_DEPENDENCIES) 
	@rm -f mpi-bench$(EXEEXT)
	$(mpi_bench_LINK) $(mpi_bench_OBJECTS) $(mpi_bench_LDADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/any-true.Plo
include ./$(DEPDIR)/api.Plo
include ./$(DEPDIR)/block.Plo
include ./$(DEPDIR)/choose-radix.Plo
include ./$(DEPDIR)/conf.Plo
include ./$(DEPDIR)/dft-problem.Plo
include ./$(DEPDIR)/dft-rank-geq2-transposed.Plo
include ./$(DEPDIR)/dft-rank-geq2.Plo
include ./$(DEPDIR)/dft-rank1-bigvec.Plo
include ./$(DEPDIR)/dft-rank1.Plo
include ./$(DEPDIR)/dft-serial.Plo
include ./$(DEPDIR)/dft-solve.Plo
include ./$(DEPDIR)/dtensor.Plo
include ./$(DEPDIR)/f03-wrap.Plo
include ./$(DEPDIR)/mpi_bench-fftw-bench.Po
include ./$(DEPDIR)/mpi_bench-hook.Po
include ./$(DEPDIR)/mpi_bench-mpi-bench.Po
include ./$(DEPDIR)/rdft-problem.Plo
include ./$(DEPDIR)/rdft-rank-geq2-transposed.Plo
include ./$(DEPDIR)/rdft-rank-geq2.Plo
include ./$(DEPDIR)/rdft-rank1-bigvec.Plo
include ./$(DEPDIR)/rdft-serial.Plo
include ./$(DEPDIR)/rdft-solve.Plo
include ./$(DEPDIR)/rdft2-problem.Plo
include ./$(DEPDIR)/rdft2-rank-geq2-transposed.Plo
include ./$(DEPDIR)/rdft2-rank-geq2.Plo
include ./$(DEPDIR)/rdft2-serial.Plo
include ./$(DEPDIR)/rdft2-solve.Plo
include ./$(DEPDIR)/rearrange.Plo
include ./$(DEPDIR)/transpose-alltoall.Plo
include ./$(DEPDIR)/transpose-pairwise.Plo
include ./$(DEPDIR)/transpose-problem.Plo
include ./$(DEPDIR)/transpose-recurse.Plo
include ./$(DEPDIR)/transpose-solve.Plo
include ./$(DEPDIR)/wisdom-api.Plo

.c.o:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c $<

.c.obj:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c `$(CYGPATH_W) '$<'`

.c.lo:
	$(LTCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Plo
#	source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(LTCOMPILE) -c -o $@ $<

mpi_bench-mpi-bench.o: mpi-bench.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -MT mpi_bench-mpi-bench.o -MD -MP -MF $(DEPDIR)/mpi_bench-mpi-bench.Tpo -c -o mpi_bench-mpi-bench.o `test -f 'mpi-bench.c' || echo '$(srcdir)/'`mpi-bench.c
	$(am__mv) $(DEPDIR)/mpi_bench-mpi-bench.Tpo $(DEPDIR)/mpi_bench-mpi-bench.Po
#	source='mpi-bench.c' object='mpi_bench-mpi-bench.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -c -o mpi_bench-mpi-bench.o `test -f 'mpi-bench.c' || echo '$(srcdir)/'`mpi-bench.c

mpi_bench-mpi-bench.obj: mpi-bench.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -MT mpi_bench-mpi-bench.obj -MD -MP -MF $(DEPDIR)/mpi_bench-mpi-bench.Tpo -c -o mpi_bench-mpi-bench.obj `if test -f 'mpi-bench.c'; then $(CYGPATH_W) 'mpi-bench.c'; else $(CYGPATH_W) '$(srcdir)/mpi-bench.c'; fi`
	$(am__mv) $(DEPDIR)/mpi_bench-mpi-bench.Tpo $(DEPDIR)/mpi_bench-mpi-bench.Po
#	source='mpi-bench.c' object='mpi_bench-mpi-bench.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -c -o mpi_bench-mpi-bench.obj `if test -f 'mpi-bench.c'; then $(CYGPATH_W) 'mpi-bench.c'; else $(CYGPATH_W) '$(srcdir)/mpi-bench.c'; fi`

mpi_bench-fftw-bench.o: $(top_srcdir)/tests/fftw-bench.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -MT mpi_bench-fftw-bench.o -MD -MP -MF $(DEPDIR)/mpi_bench-fftw-bench.Tpo -c -o mpi_bench-fftw-bench.o `test -f '$(top_srcdir)/tests/fftw-bench.c' || echo '$(srcdir)/'`$(top_srcdir)/tests/fftw-bench.c
	$(am__mv) $(DEPDIR)/mpi_bench-fftw-bench.Tpo $(DEPDIR)/mpi_bench-fftw-bench.Po
#	source='$(top_srcdir)/tests/fftw-bench.c' object='mpi_bench-fftw-bench.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -c -o mpi_bench-fftw-bench.o `test -f '$(top_srcdir)/tests/fftw-bench.c' || echo '$(srcdir)/'`$(top_srcdir)/tests/fftw-bench.c

mpi_bench-fftw-bench.obj: $(top_srcdir)/tests/fftw-bench.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -MT mpi_bench-fftw-bench.obj -MD -MP -MF $(DEPDIR)/mpi_bench-fftw-bench.Tpo -c -o mpi_bench-fftw-bench.obj `if test -f '$(top_srcdir)/tests/fftw-bench.c'; then $(CYGPATH_W) '$(top_srcdir)/tests/fftw-bench.c'; else $(CYGPATH_W) '$(srcdir)/$(top_srcdir)/tests/fftw-bench.c'; fi`
	$(am__mv) $(DEPDIR)/mpi_bench-fftw-bench.Tpo $(DEPDIR)/mpi_bench-fftw-bench.Po
#	source='$(top_srcdir)/tests/fftw-bench.c' object='mpi_bench-fftw-bench.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -c -o mpi_bench-fftw-bench.obj `if test -f '$(top_srcdir)/tests/fftw-bench.c'; then $(CYGPATH_W) '$(top_srcdir)/tests/fftw-bench.c'; else $(CYGPATH_W) '$(srcdir)/$(top_srcdir)/tests/fftw-bench.c'; fi`

mpi_bench-hook.o: $(top_srcdir)/tests/hook.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -MT mpi_bench-hook.o -MD -MP -MF $(DEPDIR)/mpi_bench-hook.Tpo -c -o mpi_bench-hook.o `test -f '$(top_srcdir)/tests/hook.c' || echo '$(srcdir)/'`$(top_srcdir)/tests/hook.c
	$(am__mv) $(DEPDIR)/mpi_bench-hook.Tpo $(DEPDIR)/mpi_bench-hook.Po
#	source='$(top_srcdir)/tests/hook.c' object='mpi_bench-hook.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -c -o mpi_bench-hook.o `test -f '$(top_srcdir)/tests/hook.c' || echo '$(srcdir)/'`$(top_srcdir)/tests/hook.c

mpi_bench-hook.obj: $(top_srcdir)/tests/hook.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -MT mpi_bench-hook.obj -MD -MP -MF $(DEPDIR)/mpi_bench-hook.Tpo -c -o mpi_bench-hook.obj `if test -f '$(top_srcdir)/tests/hook.c'; then $(CYGPATH_W) '$(top_srcdir)/tests/hook.c'; else $(CYGPATH_W) '$(srcdir)/$(top_srcdir)/tests/hook.c'; fi`
	$(am__mv) $(DEPDIR)/mpi_bench-hook.Tpo $(DEPDIR)/mpi_bench-hook.Po
#	source='$(top_srcdir)/tests/hook.c' object='mpi_bench-hook.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(mpi_bench_CFLAGS) $(CFLAGS) -c -o mpi_bench-hook.obj `if test -f '$(top_srcdir)/tests/hook.c'; then $(CYGPATH_W) '$(top_srcdir)/tests/hook.c'; else $(CYGPATH_W) '$(srcdir)/$(top_srcdir)/tests/hook.c'; fi`

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs
install-includeHEADERS: $(include_HEADERS)
	@$(NORMAL_INSTALL)
	@list='$(include_HEADERS)'; test -n "$(includedir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(includedir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(includedir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_HEADER) $$files '$(DESTDIR)$(includedir)'"; \
	  $(INSTALL_HEADER) $$files "$(DESTDIR)$(includedir)" || exit $$?; \
	done

uninstall-includeHEADERS:
	@$(NORMAL_UNINSTALL)
	@list='$(include_HEADERS)'; test -n "$(includedir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(includedir)'; $(am__uninstall_files_from_dir)
install-nodist_includeHEADERS: $(nodist_include_HEADERS)
	@$(NORMAL_INSTALL)
	@list='$(nodist_include_HEADERS)'; test -n "$(includedir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(includedir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(includedir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_HEADER) $$files '$(DESTDIR)$(includedir)'"; \
	  $(INSTALL_HEADER) $$files "$(DESTDIR)$(includedir)" || exit $$?; \
	done

uninstall-nodist_includeHEADERS:
	@$(NORMAL_UNINSTALL)
	@list='$(nodist_include_HEADERS)'; test -n "$(includedir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(includedir)'; $(am__uninstall_files_from_dir)

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: CTAGS
CTAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-local:
check-am: all-am
	$(MAKE) $(AM_MAKEFLAGS) check-local
check: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) check-am
all-am: Makefile $(LTLIBRARIES) $(PROGRAMS) $(HEADERS)
installdirs:
	for dir in "$(DESTDIR)$(libdir)" "$(DESTDIR)$(includedir)" "$(DESTDIR)$(includedir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
	-test -z "$(BUILT_SOURCES)" || rm -f $(BUILT_SOURCES)
clean: clean-am

clean-am: clean-generic clean-libLTLIBRARIES clean-libtool \
	clean-noinstPROGRAMS mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-includeHEADERS install-nodist_includeHEADERS

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-libLTLIBRARIES

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-includeHEADERS uninstall-libLTLIBRARIES \
	uninstall-nodist_includeHEADERS

.MAKE: all check check-am install install-am install-strip

.PHONY: CTAGS GTAGS all all-am check check-am check-local clean \
	clean-generic clean-libLTLIBRARIES clean-libtool \
	clean-noinstPROGRAMS ctags distclean distclean-compile \
	distclean-generic distclean-libtool distclean-tags distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-includeHEADERS install-info install-info-am \
	install-libLTLIBRARIES install-man \
	install-nodist_includeHEADERS install-pdf install-pdf-am \
	install-ps install-ps-am install-strip installcheck \
	installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags uninstall uninstall-am uninstall-includeHEADERS \
	uninstall-libLTLIBRARIES uninstall-nodist_includeHEADERS


#check-local: mpi-bench$(EXEEXT)
#	perl -w $(CHECK) $(CHECKOPTS) --mpi "$(MPIRUN) -np 1 `pwd`/mpi-bench"
#	@echo "--------------------------------------------------------------"
#	@echo "     MPI FFTW transforms passed "$(NUMCHECK)" tests, 1 CPU"
#	@echo "--------------------------------------------------------------"
#	perl -w $(CHECK) $(CHECKOPTS) --mpi "$(MPIRUN) -np 2 `pwd`/mpi-bench"
#	@echo "--------------------------------------------------------------"
#	@echo "      MPI FFTW transforms passed "$(NUMCHECK)" tests, 2 CPUs"
#	@echo "--------------------------------------------------------------"
#	perl -w $(CHECK) $(CHECKOPTS) --mpi "$(MPIRUN) -np 3 `pwd`/mpi-bench"
#	@echo "--------------------------------------------------------------"
#	@echo "      MPI FFTW transforms passed "$(NUMCHECK)" tests, 3 CPUs"
#	@echo "--------------------------------------------------------------"
#	perl -w $(CHECK) $(CHECKOPTS) --mpi "$(MPIRUN) -np 4 `pwd`/mpi-bench"
#	@echo "--------------------------------------------------------------"
#	@echo "      MPI FFTW transforms passed "$(NUMCHECK)" tests, 4 CPUs"
#	@echo "--------------------------------------------------------------"
##	perl -w $(CHECK) $(CHECKOPTS) --mpi --nthreads=2 "$(MPIRUN) -np 3 `pwd`/mpi-bench"
##	@echo "--------------------------------------------------------------"
##	@echo "      MPI FFTW threaded transforms passed "$(NUMCHECK)" tests!"
##	@echo "--------------------------------------------------------------"

#bigcheck: mpi-bench$(EXEEXT)
#	$(MAKE) $(AM_MAKEFLAGS) NUMCHECK=100 CHECKSIZE=60000 check-local

#smallcheck: mpi-bench$(EXEEXT)
#	$(MAKE) $(AM_MAKEFLAGS) NUMCHECK=2 check-local

fftw3-mpi.f03: fftw3-mpi.f03.in
	sed 's/C_MPI_FINT//' $(srcdir)/fftw3-mpi.f03.in > $@

fftw3l-mpi.f03: fftw3l-mpi.f03.in
	sed 's/C_MPI_FINT//' $(srcdir)/fftw3l-mpi.f03.in > $@

#fftw3-mpi.f03.in: fftw3-mpi.h f03api.sh $(top_srcdir)/api/genf03.pl
#	sh $(srcdir)/f03api.sh d f > $@

#fftw3l-mpi.f03.in: fftw3-mpi.h f03api.sh $(top_srcdir)/api/genf03.pl
#	sh $(srcdir)/f03api.sh l | grep -v parameter | sed 's/fftw3.f03/fftw3l.f03/' > $@

#f03-wrap.c: fftw3-mpi.h f03-wrap.sh genf03-wrap.pl
#	sh $(srcdir)/f03-wrap.sh > $@

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
