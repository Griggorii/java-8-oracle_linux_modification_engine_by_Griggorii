# java-8-oracle_linux_modification_engine_by_Griggorii
java-8 , oracle , android , java , modification , jar , shell , jdb , обратные совместимости , embedded , javac , jdk , xml , dtd , schemagen , jcpp java c  preprocessor , jdeps , jmap , extcheck , jarsigner , appletviewer , rmiregistry , pack200 , unpack200 , jsadebugd , jps , jexec , nano linux engine

Install my tarball https://yadi.sk/d/eBjX-DNHtg5xtw

https://www.youtube.com/watch?v=kyNk8b4Z4ik

Griggorii@gmail.com только настоящие технологии bitcoin support real technology new fix 1Fps612daCcb7vYN2bFDRoDuUnrjJESDmk

Example all programm development griggorii java-8 modification folder buildroot-master in locate /tmp

.1/buildroot-build
>>> llvm 10.0.0 Building
PATH="/tmp/buildroot-master/output/host/bin:/tmp/buildroot-master/output/host/sbin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/games:/usr/local/games:/usr/lib/jvm/java-8-oracle/bin:/usr/lib/jvm/java-8-oracle/db/bin:/usr/lib/jvm/java-8-oracle/jre/bin"  /usr/bin/make -j5  -C /tmp/buildroot-master/output/build/llvm-10.0.0//buildroot-build

____________________________________________________________________________________________________________________________________________________

Javac example

dnl @synopsis AC_PROG_JAVAC
dnl
dnl AC_PROG_JAVAC tests an existing Java compiler. It uses the environment
dnl variable JAVAC then tests in sequence various common Java compilers. For
dnl political reasons, it starts with the free ones.
dnl
dnl If you want to force a specific compiler:
dnl
dnl - at the configure.in level, set JAVAC=yourcompiler before calling
dnl AC_PROG_JAVAC
dnl
dnl - at the configure level, setenv JAVAC
dnl
dnl You can use the JAVAC variable in your Makefile.in, with @JAVAC@.
dnl
dnl *Warning*: its success or failure can depend on a proper setting of the
dnl CLASSPATH env. variable.
dnl
dnl TODO: allow to exclude compilers (rationale: most Java programs cannot compile
dnl with some compilers like guavac).
dnl
dnl Note: This is part of the set of autoconf M4 macros for Java programs.
dnl It is VERY IMPORTANT that you download the whole set, some
dnl macros depend on other. Unfortunately, the autoconf archive does not
dnl support the concept of set of macros, so I had to break it for
dnl submission.
dnl The general documentation, as well as the sample configure.in, is
dnl included in the AC_PROG_JAVA macro.
dnl
dnl @author Stephane Bortzmeyer <bortzmeyer@pasteur.fr>
dnl @version $Id$
dnl
AC_DEFUN([AC_PROG_JAVAC],[
AC_REQUIRE([AC_EXEEXT])dnl
if test "x$JAVAPREFIX" = x; then
        test "x$JAVAC" = x && AC_CHECK_PROGS(JAVAC, javac$EXEEXT "gcj$EXEEXT -C" guavac$EXEEXT jikes$EXEEXT)
else
        test "x$JAVAC" = x && AC_CHECK_PROGS(JAVAC, javac$EXEEXT "gcj$EXEEXT -C" guavac$EXEEXT jikes$EXEEXT, $JAVAPREFIX)
fi
test "x$JAVAC" = x && AC_MSG_ERROR([no acceptable Java compiler found in \$PATH])
AC_PROG_JAVAC_WORKS
AC_PROVIDE([$0])dnl
])
