# java-8-oracle_linux_modification_engine_by_Griggorii
java-8 , oracle , android , java , modification , jar , shell , jdb , обратные совместимости , embedded , javac , jdk , xml , dtd , schemagen , jcpp java c  preprocessor , jdeps , jmap , extcheck , jarsigner , appletviewer , rmiregistry , pack200 , unpack200 , jsadebugd , jps , jexec , nano linux engine

Install my tarball java-8-oracle_linux https://yadi.sk/d/eBjX-DNHtg5xtw

https://www.youtube.com/watch?v=kyNk8b4Z4ik

$ sudo ln -s /usr/lib/jvm/java-8-oracle/bin/* /usr/bin

Not found link ? check example not link policytool open /usr/lib/jvm/java-8-oracle/bin

$ sudo ln -s /usr/lib/jvm/java-8-oracle/bin/policytool /usr/bin

$ sudo nano /etc/environment

Add new string /etc/environment save java_home  

JAVA_HOME="/usr/lib/jvm/java-8-oracle"

Reboot check 

$ echo $JAVA_HOME

+ good instrument https://github.com/pxb1988/dex2jar/releases

+ https://github.com/java-decompiler/jd-gui/releases/ deb install fix $ sudo nano '/opt/jd-gui/jd-gui.desktop' replace string 4) Exec=java -jar /opt/jd-gui/jd-gui.jar to fix ->  Exec=java -jarsudo nano d-gui/jd-gui-1.6.6-min.jar

Only real technologies, not any fictional parasitic distributions support real technology investments and donate VISA 4817 7601 8112 4706 griggorii@gmail.com while developing and submitting information here, I cannot be distracted even by half of freelancing, so any help on a dollar card will help to implement explanatory actions much wider with a more understandable presentation / it is proposed to decompile the entire java class and build a new chromium browser already from the cleaned java code based on apk that will be compiled for both android and linux \ windows \ MacOS, especially since there is such help as dtd circuits on a java engine that would not download 1000 or more gigabytes of raw materials in the future, and in the future it will no longer be unusual, but it would be a stupid decision to bring it to this point when the entire interface can be converted to a java engine with the knowledge that apk can be used to make an executable extension in chromium from apk similar browsers and natively via java name.jar or java -jarname .jar in some cases the contents of the (data) <- which can be created with the scheme can work like a real android, this knowledge will help you figure out in some cases why the application did not start. Since some are much better developers, but I am just passing on how this can be implemented based on my idea, an example https://github.com/Griggorii/Midori-Web-Browser-ubuntu-18.10/blob/master/Midori-browser-by_Griggorii- dex2jar.jar_source_from_JADX.zip there is also such an idea, but getting bugs indigestible squares is several times higher https://youtu.be/k6EGJOsB3fQ squares are most likely these assembly paths at the processor level that are not digested from the first time of the type as an example> {"\u0000<\n\u0002\n\u00a8\u0006\u001e"}

Только настоящие технологии ни каких выдуманных паразитирующих дистрибутивов support real technology investments and donate VISA 4817 7601 8112 4706 griggorii@gmail.com занимаясь разработками и подачей информации сюда я не могу отвлечься даже на пол фриланса так что любая помощь на доллоровую карту поможет  реализовывать объяснительные действия гораздо шире с более понятной подачей / предлагается декомпелировать весь java class и строить новый chromium браузер уже из очищенного java кода на основе apk который будет собираться как для андроида так и для linux\windows\MacOS тем более есть такая помощь как dtd схемы на java двигателе что бы не скачивать в будущем 1000 и более гигабайт сырцов , а в будущем это уже не будет не обычным , но это будет глупым решением довести до этого когда весь интерфеис можно переконвертировать в java двигатель с тем знанием что из apk можно сделать запускаемое расширение эксчеиндж в chromium подобных браузерах и нативно через java name.jar или java -jarname.jar в некоторых случаях содержимое папки (data) <- которую можно создать со схемой может работать как самый настоящий андроид вот эти знания помогут вам разгадать в некотрых вариантах почему не запустилось приложение. По скольку некотрые являются гораздо лучшими разработчиками , а лишь передаю как это можно реализовать на основе моей идеи пример https://github.com/Griggorii/Midori-Web-Browser-ubuntu-18.10/blob/master/Midori-browser-by_Griggorii-dex2jar.jar_source_from_JADX.zip так же есть такая идея , но получить баги не переваримые квадратики в разы выше https://youtu.be/k6EGJOsB3fQ квадратики это скорее всего вот эти ассемблерные пути на уровне процессора которые не перевариваются с первого раза типа как пример -> {"\u0000<\n\u0002\n\u00a8\u0006\u001e"}

Example all programm development griggorii java-8 modification folder buildroot-master in locate /tmp

Example OS buld compilator switch java-8-oracle disk.iso download https://github.com/Griggorii/dahliaOS_iso_java-8-oracle/releases/tag/dahliaOS

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
