# This Makefile is for the Devel::PerlySense extension to perl.
#
# It was generated automatically by MakeMaker version
# 7.34 (Revision: 73400) from the contents of
# Makefile.PL. Don't edit this file, edit Makefile.PL instead.
#
#       ANY CHANGES MADE HERE WILL BE LOST!
#
#   MakeMaker ARGV: ()
#

#   MakeMaker Parameters:

#     ABSTRACT => q[Perl IDE backend with Emacs frontend]
#     AUTHOR => [q[Johan Lindstrom <johanl@cpan.org>]]
#     BUILD_REQUIRES => {  }
#     CONFIGURE_REQUIRES => { ExtUtils::MakeMaker=>q[0] }
#     DISTNAME => q[Devel-PerlySense]
#     EXE_FILES => [q[bin/perly_sense]]
#     LICENSE => q[perl]
#     NAME => q[Devel::PerlySense]
#     PREREQ_PM => { App::Ack=>q[0], Cache::Cache=>q[0], Cache::FileCache=>q[0], Carp=>q[0], Class::MethodMaker=>q[0], Cwd=>q[0], Data::Dumper=>q[0], Digest::SHA=>q[0], Exception::Class=>q[0], Exporter=>q[0], File::Basename=>q[0], File::Find=>q[0], File::Find::Rule=>q[0], File::Path=>q[0], File::Slurp=>q[0], File::Spec=>q[0], File::Spec::Functions=>q[0], File::Temp=>q[0], File::chdir=>q[0], Getopt::Long=>q[0], Graph::Easy=>q[0], HTTP::Date=>q[0], IO::String=>q[0], List::AllUtils=>q[0], List::MoreUtils=>q[0], List::Util=>q[0], Module::Pluggable=>q[3.5], Module::Runtime=>q[0], Moo=>q[0], POSIX=>q[0], PPI=>q[1.003], PPI::Document=>q[0], PPI::Dumper=>q[0], Params::Util=>q[0], Path::Class=>q[0.11], Path::Tiny=>q[0], Perl::Critic=>q[1.105], Perl::Tidy=>q[0], Pod::Text=>q[0], Pod::Usage=>q[0], Spiffy=>q[0], Storable=>q[0], Sub::Exporter=>q[0], Test::Differences=>q[0], Test::Exception=>q[0], Test::More=>q[0], Text::Table=>q[0], Time::HiRes=>q[0], Tree::Parser=>q[0], YAML::Tiny=>q[0], base=>q[0], lib=>q[0], strict=>q[0], utf8=>q[0], warnings=>q[0] }
#     TEST_REQUIRES => { Class::MethodMaker=>q[0], Exception::Class=>q[0], File::Spec=>q[0], File::Temp=>q[0], Test::Differences=>q[0], Test::Exception=>q[0], Test::More=>q[0] }
#     VERSION => q[0.0222]
#     test => { TESTS=>q[t/*.t t/data/project/with-dir/source/t/*.t t/data/project/with-git/source/bogus/t/*.t t/data/project/with-perlysenseproject/source/bogus/t/*.t] }

# --- MakeMaker post_initialize section:


# --- MakeMaker const_config section:

# These definitions are from config.sh (via /usr/lib64/perl5/Config.pm).
# They may have been overridden via Makefile.PL or on the command line.
AR = ar
CC = gcc
CCCDLFLAGS = -fPIC
CCDLFLAGS = -Wl,--enable-new-dtags -Wl,-z,relro -Wl,-z,now -specs=/usr/lib/rpm/redhat/redhat-hardened-ld
DLEXT = so
DLSRC = dl_dlopen.xs
EXE_EXT = 
FULL_AR = /usr/bin/ar
LD = gcc
LDDLFLAGS = -lpthread -shared -Wl,-z,relro -Wl,-z,now -specs=/usr/lib/rpm/redhat/redhat-hardened-ld -L/usr/local/lib -fstack-protector-strong
LDFLAGS = -Wl,-z,relro -Wl,-z,now -specs=/usr/lib/rpm/redhat/redhat-hardened-ld -fstack-protector-strong -L/usr/local/lib
LIBC = libc-2.28.so
LIB_EXT = .a
OBJ_EXT = .o
OSNAME = linux
OSVERS = 4.19.34-300.el7.x86_64
RANLIB = :
SITELIBEXP = /usr/local/share/perl5
SITEARCHEXP = /usr/local/lib64/perl5
SO = so
VENDORARCHEXP = /usr/lib64/perl5/vendor_perl
VENDORLIBEXP = /usr/share/perl5/vendor_perl


# --- MakeMaker constants section:
AR_STATIC_ARGS = cr
DIRFILESEP = /
DFSEP = $(DIRFILESEP)
NAME = Devel::PerlySense
NAME_SYM = Devel_PerlySense
VERSION = 0.0222
VERSION_MACRO = VERSION
VERSION_SYM = 0_0222
DEFINE_VERSION = -D$(VERSION_MACRO)=\"$(VERSION)\"
XS_VERSION = 0.0222
XS_VERSION_MACRO = XS_VERSION
XS_DEFINE_VERSION = -D$(XS_VERSION_MACRO)=\"$(XS_VERSION)\"
INST_ARCHLIB = blib/arch
INST_SCRIPT = blib/script
INST_BIN = blib/bin
INST_LIB = blib/lib
INST_MAN1DIR = blib/man1
INST_MAN3DIR = blib/man3
MAN1EXT = 1
MAN3EXT = 3pm
INSTALLDIRS = site
DESTDIR = 
PREFIX = $(SITEPREFIX)
PERLPREFIX = /usr
SITEPREFIX = /usr/local
VENDORPREFIX = /usr
INSTALLPRIVLIB = /usr/share/perl5
DESTINSTALLPRIVLIB = $(DESTDIR)$(INSTALLPRIVLIB)
INSTALLSITELIB = /usr/local/share/perl5
DESTINSTALLSITELIB = $(DESTDIR)$(INSTALLSITELIB)
INSTALLVENDORLIB = /usr/share/perl5/vendor_perl
DESTINSTALLVENDORLIB = $(DESTDIR)$(INSTALLVENDORLIB)
INSTALLARCHLIB = /usr/lib64/perl5
DESTINSTALLARCHLIB = $(DESTDIR)$(INSTALLARCHLIB)
INSTALLSITEARCH = /usr/local/lib64/perl5
DESTINSTALLSITEARCH = $(DESTDIR)$(INSTALLSITEARCH)
INSTALLVENDORARCH = /usr/lib64/perl5/vendor_perl
DESTINSTALLVENDORARCH = $(DESTDIR)$(INSTALLVENDORARCH)
INSTALLBIN = /usr/bin
DESTINSTALLBIN = $(DESTDIR)$(INSTALLBIN)
INSTALLSITEBIN = /usr/local/bin
DESTINSTALLSITEBIN = $(DESTDIR)$(INSTALLSITEBIN)
INSTALLVENDORBIN = /usr/bin
DESTINSTALLVENDORBIN = $(DESTDIR)$(INSTALLVENDORBIN)
INSTALLSCRIPT = /usr/bin
DESTINSTALLSCRIPT = $(DESTDIR)$(INSTALLSCRIPT)
INSTALLSITESCRIPT = /usr/local/bin
DESTINSTALLSITESCRIPT = $(DESTDIR)$(INSTALLSITESCRIPT)
INSTALLVENDORSCRIPT = /usr/bin
DESTINSTALLVENDORSCRIPT = $(DESTDIR)$(INSTALLVENDORSCRIPT)
INSTALLMAN1DIR = /usr/share/man/man1
DESTINSTALLMAN1DIR = $(DESTDIR)$(INSTALLMAN1DIR)
INSTALLSITEMAN1DIR = /usr/local/share/man/man1
DESTINSTALLSITEMAN1DIR = $(DESTDIR)$(INSTALLSITEMAN1DIR)
INSTALLVENDORMAN1DIR = /usr/share/man/man1
DESTINSTALLVENDORMAN1DIR = $(DESTDIR)$(INSTALLVENDORMAN1DIR)
INSTALLMAN3DIR = /usr/share/man/man3
DESTINSTALLMAN3DIR = $(DESTDIR)$(INSTALLMAN3DIR)
INSTALLSITEMAN3DIR = /usr/local/share/man/man3
DESTINSTALLSITEMAN3DIR = $(DESTDIR)$(INSTALLSITEMAN3DIR)
INSTALLVENDORMAN3DIR = /usr/share/man/man3
DESTINSTALLVENDORMAN3DIR = $(DESTDIR)$(INSTALLVENDORMAN3DIR)
PERL_LIB = /usr/share/perl5
PERL_ARCHLIB = /usr/lib64/perl5
PERL_ARCHLIBDEP = /usr/lib64/perl5
LIBPERL_A = libperl.a
FIRST_MAKEFILE = Makefile
MAKEFILE_OLD = Makefile.old
MAKE_APERL_FILE = Makefile.aperl
PERLMAINCC = $(CC)
PERL_INC = /usr/lib64/perl5/CORE
PERL_INCDEP = /usr/lib64/perl5/CORE
PERL = "/usr/bin/perl"
FULLPERL = "/usr/bin/perl"
ABSPERL = $(PERL)
PERLRUN = $(PERL)
FULLPERLRUN = $(FULLPERL)
ABSPERLRUN = $(ABSPERL)
PERLRUNINST = $(PERLRUN) "-I$(INST_ARCHLIB)" "-I$(INST_LIB)"
FULLPERLRUNINST = $(FULLPERLRUN) "-I$(INST_ARCHLIB)" "-I$(INST_LIB)"
ABSPERLRUNINST = $(ABSPERLRUN) "-I$(INST_ARCHLIB)" "-I$(INST_LIB)"
PERL_CORE = 0
PERM_DIR = 755
PERM_RW = 644
PERM_RWX = 755

MAKEMAKER   = /usr/share/perl5/vendor_perl/ExtUtils/MakeMaker.pm
MM_VERSION  = 7.34
MM_REVISION = 73400

# FULLEXT = Pathname for extension directory (eg Foo/Bar/Oracle).
# BASEEXT = Basename part of FULLEXT. May be just equal FULLEXT. (eg Oracle)
# PARENT_NAME = NAME without BASEEXT and no trailing :: (eg Foo::Bar)
# DLBASE  = Basename part of dynamic library. May be just equal BASEEXT.
MAKE = make
FULLEXT = Devel/PerlySense
BASEEXT = PerlySense
PARENT_NAME = Devel
DLBASE = $(BASEEXT)
VERSION_FROM = 
OBJECT = 
LDFROM = $(OBJECT)
LINKTYPE = dynamic
BOOTDEP = 

# Handy lists of source code files:
XS_FILES = 
C_FILES  = 
O_FILES  = 
H_FILES  = 
MAN1PODS = bin/perly_sense
MAN3PODS = lib/Devel/PerlySense.pm \
	lib/Devel/PerlySense/Bookmark/Definition.pm \
	lib/Devel/PerlySense/Bookmark/Match.pm \
	lib/Devel/PerlySense/Bookmark/MatchResult.pm \
	lib/Devel/PerlySense/BookmarkConfig.pm \
	lib/Devel/PerlySense/CallTree.pm \
	lib/Devel/PerlySense/CallTree/Caller.pm \
	lib/Devel/PerlySense/CallTree/Graph.pm \
	lib/Devel/PerlySense/Class.pm \
	lib/Devel/PerlySense/Config/Project.pm \
	lib/Devel/PerlySense/Config/Project/Default.pm \
	lib/Devel/PerlySense/Cookbook.pod \
	lib/Devel/PerlySense/Document.pm \
	lib/Devel/PerlySense/Document/Api.pm \
	lib/Devel/PerlySense/Document/Api/Method.pm \
	lib/Devel/PerlySense/Document/Location.pm \
	lib/Devel/PerlySense/Document/Meta.pm \
	lib/Devel/PerlySense/Editor.pm \
	lib/Devel/PerlySense/Editor/Emacs.pm \
	lib/Devel/PerlySense/Editor/Vim.pm \
	lib/Devel/PerlySense/Home.pm \
	lib/Devel/PerlySense/Plugin/Syntax/Moose.pm \
	lib/Devel/PerlySense/Project.pm \
	lib/Devel/PerlySense/Project/Unknown.pm \
	lib/Devel/PerlySense/Util.pm \
	lib/Devel/PerlySense/Util/Log.pm \
	lib/Devel/TimeThis.pm

# Where is the Config information that we are using/depend on
CONFIGDEP = $(PERL_ARCHLIBDEP)$(DFSEP)Config.pm $(PERL_INCDEP)$(DFSEP)config.h

# Where to build things
INST_LIBDIR      = $(INST_LIB)/Devel
INST_ARCHLIBDIR  = $(INST_ARCHLIB)/Devel

INST_AUTODIR     = $(INST_LIB)/auto/$(FULLEXT)
INST_ARCHAUTODIR = $(INST_ARCHLIB)/auto/$(FULLEXT)

INST_STATIC      = 
INST_DYNAMIC     = 
INST_BOOT        = 

# Extra linker info
EXPORT_LIST        = 
PERL_ARCHIVE       = 
PERL_ARCHIVEDEP    = 
PERL_ARCHIVE_AFTER = 


TO_INST_PM = lib/Devel/PerlySense.pm \
	lib/Devel/PerlySense/Bookmark/Definition.pm \
	lib/Devel/PerlySense/Bookmark/Match.pm \
	lib/Devel/PerlySense/Bookmark/MatchResult.pm \
	lib/Devel/PerlySense/BookmarkConfig.pm \
	lib/Devel/PerlySense/CallTree.pm \
	lib/Devel/PerlySense/CallTree/Caller.pm \
	lib/Devel/PerlySense/CallTree/Graph.pm \
	lib/Devel/PerlySense/Class.pm \
	lib/Devel/PerlySense/Config/Project.pm \
	lib/Devel/PerlySense/Config/Project/Default.pm \
	lib/Devel/PerlySense/Cookbook.pod \
	lib/Devel/PerlySense/Document.pm \
	lib/Devel/PerlySense/Document/Api.pm \
	lib/Devel/PerlySense/Document/Api/Method.pm \
	lib/Devel/PerlySense/Document/Location.pm \
	lib/Devel/PerlySense/Document/Meta.pm \
	lib/Devel/PerlySense/Editor.pm \
	lib/Devel/PerlySense/Editor/Emacs.pm \
	lib/Devel/PerlySense/Editor/Vim.pm \
	lib/Devel/PerlySense/Home.pm \
	lib/Devel/PerlySense/Plugin/Syntax/Moose.pm \
	lib/Devel/PerlySense/Project.pm \
	lib/Devel/PerlySense/Project/Unknown.pm \
	lib/Devel/PerlySense/Util.pm \
	lib/Devel/PerlySense/Util/Log.pm \
	lib/Devel/PerlySense/external/emacs/async-shell-command-to-string.el \
	lib/Devel/PerlySense/external/emacs/dropdown-list.el \
	lib/Devel/PerlySense/external/emacs/lib/lang-refactor-perl.el \
	lib/Devel/PerlySense/external/emacs/perly-sense-flymake.el \
	lib/Devel/PerlySense/external/emacs/perly-sense-test-class.el \
	lib/Devel/PerlySense/external/emacs/perly-sense-visualize-coverage.el \
	lib/Devel/PerlySense/external/emacs/perly-sense.el \
	lib/Devel/PerlySense/external/emacs/regex-tool.el \
	lib/Devel/PerlySense/external/emacs/shell-command-pool.el \
	lib/Devel/TimeThis.pm


# --- MakeMaker platform_constants section:
MM_Unix_VERSION = 7.34
PERL_MALLOC_DEF = -DPERL_EXTMALLOC_DEF -Dmalloc=Perl_malloc -Dfree=Perl_mfree -Drealloc=Perl_realloc -Dcalloc=Perl_calloc


# --- MakeMaker tool_autosplit section:
# Usage: $(AUTOSPLITFILE) FileToSplit AutoDirToSplitInto
AUTOSPLITFILE = $(ABSPERLRUN)  -e 'use AutoSplit;  autosplit($$$$ARGV[0], $$$$ARGV[1], 0, 1, 1)' --



# --- MakeMaker tool_xsubpp section:


# --- MakeMaker tools_other section:
SHELL = /bin/sh
CHMOD = chmod
CP = cp
MV = mv
NOOP = $(TRUE)
NOECHO = @
RM_F = rm -f
RM_RF = rm -rf
TEST_F = test -f
TOUCH = touch
UMASK_NULL = umask 0
DEV_NULL = > /dev/null 2>&1
MKPATH = $(ABSPERLRUN) -MExtUtils::Command -e 'mkpath' --
EQUALIZE_TIMESTAMP = $(ABSPERLRUN) -MExtUtils::Command -e 'eqtime' --
FALSE = false
TRUE = true
ECHO = echo
ECHO_N = echo -n
UNINST = 0
VERBINST = 0
MOD_INSTALL = $(ABSPERLRUN) -MExtUtils::Install -e 'install([ from_to => {@ARGV}, verbose => '\''$(VERBINST)'\'', uninstall_shadows => '\''$(UNINST)'\'', dir_mode => '\''$(PERM_DIR)'\'' ]);' --
DOC_INSTALL = $(ABSPERLRUN) -MExtUtils::Command::MM -e 'perllocal_install' --
UNINSTALL = $(ABSPERLRUN) -MExtUtils::Command::MM -e 'uninstall' --
WARN_IF_OLD_PACKLIST = $(ABSPERLRUN) -MExtUtils::Command::MM -e 'warn_if_old_packlist' --
MACROSTART = 
MACROEND = 
USEMAKEFILE = -f
FIXIN = $(ABSPERLRUN) -MExtUtils::MY -e 'MY->fixin(shift)' --
CP_NONEMPTY = $(ABSPERLRUN) -MExtUtils::Command::MM -e 'cp_nonempty' --


# --- MakeMaker makemakerdflt section:
makemakerdflt : all
	$(NOECHO) $(NOOP)


# --- MakeMaker dist section:
TAR = tar
TARFLAGS = cvf
ZIP = zip
ZIPFLAGS = -r
COMPRESS = gzip --best
SUFFIX = .gz
SHAR = shar
PREOP = $(NOECHO) $(NOOP)
POSTOP = $(NOECHO) $(NOOP)
TO_UNIX = $(NOECHO) $(NOOP)
CI = ci -u
RCS_LABEL = rcs -Nv$(VERSION_SYM): -q
DIST_CP = best
DIST_DEFAULT = tardist
DISTNAME = Devel-PerlySense
DISTVNAME = Devel-PerlySense-0.0222


# --- MakeMaker macro section:


# --- MakeMaker depend section:


# --- MakeMaker cflags section:


# --- MakeMaker const_loadlibs section:


# --- MakeMaker const_cccmd section:


# --- MakeMaker post_constants section:


# --- MakeMaker pasthru section:

PASTHRU = LIBPERL_A="$(LIBPERL_A)"\
	LINKTYPE="$(LINKTYPE)"\
	PREFIX="$(PREFIX)"\
	PASTHRU_DEFINE='$(DEFINE) $(PASTHRU_DEFINE)'\
	PASTHRU_INC='$(INC) $(PASTHRU_INC)'


# --- MakeMaker special_targets section:
.SUFFIXES : .xs .c .C .cpp .i .s .cxx .cc $(OBJ_EXT)

.PHONY: all config static dynamic test linkext manifest blibdirs clean realclean disttest distdir pure_all subdirs clean_subdirs makemakerdflt manifypods realclean_subdirs subdirs_dynamic subdirs_pure_nolink subdirs_static subdirs-test_dynamic subdirs-test_static test_dynamic test_static



# --- MakeMaker c_o section:


# --- MakeMaker xs_c section:


# --- MakeMaker xs_o section:


# --- MakeMaker top_targets section:
all :: pure_all manifypods
	$(NOECHO) $(NOOP)

pure_all :: config pm_to_blib subdirs linkext
	$(NOECHO) $(NOOP)

	$(NOECHO) $(NOOP)

subdirs :: $(MYEXTLIB)
	$(NOECHO) $(NOOP)

config :: $(FIRST_MAKEFILE) blibdirs
	$(NOECHO) $(NOOP)

help :
	perldoc ExtUtils::MakeMaker


# --- MakeMaker blibdirs section:
blibdirs : $(INST_LIBDIR)$(DFSEP).exists $(INST_ARCHLIB)$(DFSEP).exists $(INST_AUTODIR)$(DFSEP).exists $(INST_ARCHAUTODIR)$(DFSEP).exists $(INST_BIN)$(DFSEP).exists $(INST_SCRIPT)$(DFSEP).exists $(INST_MAN1DIR)$(DFSEP).exists $(INST_MAN3DIR)$(DFSEP).exists
	$(NOECHO) $(NOOP)

# Backwards compat with 6.18 through 6.25
blibdirs.ts : blibdirs
	$(NOECHO) $(NOOP)

$(INST_LIBDIR)$(DFSEP).exists :: Makefile.PL
	$(NOECHO) $(MKPATH) $(INST_LIBDIR)
	$(NOECHO) $(CHMOD) $(PERM_DIR) $(INST_LIBDIR)
	$(NOECHO) $(TOUCH) $(INST_LIBDIR)$(DFSEP).exists

$(INST_ARCHLIB)$(DFSEP).exists :: Makefile.PL
	$(NOECHO) $(MKPATH) $(INST_ARCHLIB)
	$(NOECHO) $(CHMOD) $(PERM_DIR) $(INST_ARCHLIB)
	$(NOECHO) $(TOUCH) $(INST_ARCHLIB)$(DFSEP).exists

$(INST_AUTODIR)$(DFSEP).exists :: Makefile.PL
	$(NOECHO) $(MKPATH) $(INST_AUTODIR)
	$(NOECHO) $(CHMOD) $(PERM_DIR) $(INST_AUTODIR)
	$(NOECHO) $(TOUCH) $(INST_AUTODIR)$(DFSEP).exists

$(INST_ARCHAUTODIR)$(DFSEP).exists :: Makefile.PL
	$(NOECHO) $(MKPATH) $(INST_ARCHAUTODIR)
	$(NOECHO) $(CHMOD) $(PERM_DIR) $(INST_ARCHAUTODIR)
	$(NOECHO) $(TOUCH) $(INST_ARCHAUTODIR)$(DFSEP).exists

$(INST_BIN)$(DFSEP).exists :: Makefile.PL
	$(NOECHO) $(MKPATH) $(INST_BIN)
	$(NOECHO) $(CHMOD) $(PERM_DIR) $(INST_BIN)
	$(NOECHO) $(TOUCH) $(INST_BIN)$(DFSEP).exists

$(INST_SCRIPT)$(DFSEP).exists :: Makefile.PL
	$(NOECHO) $(MKPATH) $(INST_SCRIPT)
	$(NOECHO) $(CHMOD) $(PERM_DIR) $(INST_SCRIPT)
	$(NOECHO) $(TOUCH) $(INST_SCRIPT)$(DFSEP).exists

$(INST_MAN1DIR)$(DFSEP).exists :: Makefile.PL
	$(NOECHO) $(MKPATH) $(INST_MAN1DIR)
	$(NOECHO) $(CHMOD) $(PERM_DIR) $(INST_MAN1DIR)
	$(NOECHO) $(TOUCH) $(INST_MAN1DIR)$(DFSEP).exists

$(INST_MAN3DIR)$(DFSEP).exists :: Makefile.PL
	$(NOECHO) $(MKPATH) $(INST_MAN3DIR)
	$(NOECHO) $(CHMOD) $(PERM_DIR) $(INST_MAN3DIR)
	$(NOECHO) $(TOUCH) $(INST_MAN3DIR)$(DFSEP).exists



# --- MakeMaker linkext section:

linkext :: dynamic
	$(NOECHO) $(NOOP)


# --- MakeMaker dlsyms section:


# --- MakeMaker dynamic_bs section:

BOOTSTRAP =


# --- MakeMaker dynamic section:

dynamic :: $(FIRST_MAKEFILE) config $(INST_BOOT) $(INST_DYNAMIC)
	$(NOECHO) $(NOOP)


# --- MakeMaker dynamic_lib section:


# --- MakeMaker static section:

## $(INST_PM) has been moved to the all: target.
## It remains here for awhile to allow for old usage: "make static"
static :: $(FIRST_MAKEFILE) $(INST_STATIC)
	$(NOECHO) $(NOOP)


# --- MakeMaker static_lib section:


# --- MakeMaker manifypods section:

POD2MAN_EXE = $(PERLRUN) "-MExtUtils::Command::MM" -e pod2man "--"
POD2MAN = $(POD2MAN_EXE)


manifypods : pure_all config  \
	bin/perly_sense \
	lib/Devel/PerlySense.pm \
	lib/Devel/PerlySense/Bookmark/Definition.pm \
	lib/Devel/PerlySense/Bookmark/Match.pm \
	lib/Devel/PerlySense/Bookmark/MatchResult.pm \
	lib/Devel/PerlySense/BookmarkConfig.pm \
	lib/Devel/PerlySense/CallTree.pm \
	lib/Devel/PerlySense/CallTree/Caller.pm \
	lib/Devel/PerlySense/CallTree/Graph.pm \
	lib/Devel/PerlySense/Class.pm \
	lib/Devel/PerlySense/Config/Project.pm \
	lib/Devel/PerlySense/Config/Project/Default.pm \
	lib/Devel/PerlySense/Cookbook.pod \
	lib/Devel/PerlySense/Document.pm \
	lib/Devel/PerlySense/Document/Api.pm \
	lib/Devel/PerlySense/Document/Api/Method.pm \
	lib/Devel/PerlySense/Document/Location.pm \
	lib/Devel/PerlySense/Document/Meta.pm \
	lib/Devel/PerlySense/Editor.pm \
	lib/Devel/PerlySense/Editor/Emacs.pm \
	lib/Devel/PerlySense/Editor/Vim.pm \
	lib/Devel/PerlySense/Home.pm \
	lib/Devel/PerlySense/Plugin/Syntax/Moose.pm \
	lib/Devel/PerlySense/Project.pm \
	lib/Devel/PerlySense/Project/Unknown.pm \
	lib/Devel/PerlySense/Util.pm \
	lib/Devel/PerlySense/Util/Log.pm \
	lib/Devel/TimeThis.pm
	$(NOECHO) $(POD2MAN) --section=1 --perm_rw=$(PERM_RW) -u \
	  bin/perly_sense $(INST_MAN1DIR)/perly_sense.$(MAN1EXT) 
	$(NOECHO) $(POD2MAN) --section=3 --perm_rw=$(PERM_RW) -u \
	  lib/Devel/PerlySense.pm $(INST_MAN3DIR)/Devel::PerlySense.$(MAN3EXT) \
	  lib/Devel/PerlySense/Bookmark/Definition.pm $(INST_MAN3DIR)/Devel::PerlySense::Bookmark::Definition.$(MAN3EXT) \
	  lib/Devel/PerlySense/Bookmark/Match.pm $(INST_MAN3DIR)/Devel::PerlySense::Bookmark::Match.$(MAN3EXT) \
	  lib/Devel/PerlySense/Bookmark/MatchResult.pm $(INST_MAN3DIR)/Devel::PerlySense::Bookmark::MatchResult.$(MAN3EXT) \
	  lib/Devel/PerlySense/BookmarkConfig.pm $(INST_MAN3DIR)/Devel::PerlySense::BookmarkConfig.$(MAN3EXT) \
	  lib/Devel/PerlySense/CallTree.pm $(INST_MAN3DIR)/Devel::PerlySense::CallTree.$(MAN3EXT) \
	  lib/Devel/PerlySense/CallTree/Caller.pm $(INST_MAN3DIR)/Devel::PerlySense::CallTree::Caller.$(MAN3EXT) \
	  lib/Devel/PerlySense/CallTree/Graph.pm $(INST_MAN3DIR)/Devel::PerlySense::CallTree::Graph.$(MAN3EXT) \
	  lib/Devel/PerlySense/Class.pm $(INST_MAN3DIR)/Devel::PerlySense::Class.$(MAN3EXT) \
	  lib/Devel/PerlySense/Config/Project.pm $(INST_MAN3DIR)/Devel::PerlySense::Config::Project.$(MAN3EXT) \
	  lib/Devel/PerlySense/Config/Project/Default.pm $(INST_MAN3DIR)/Devel::PerlySense::Config::Project::Default.$(MAN3EXT) \
	  lib/Devel/PerlySense/Cookbook.pod $(INST_MAN3DIR)/Devel::PerlySense::Cookbook.$(MAN3EXT) \
	  lib/Devel/PerlySense/Document.pm $(INST_MAN3DIR)/Devel::PerlySense::Document.$(MAN3EXT) \
	  lib/Devel/PerlySense/Document/Api.pm $(INST_MAN3DIR)/Devel::PerlySense::Document::Api.$(MAN3EXT) \
	  lib/Devel/PerlySense/Document/Api/Method.pm $(INST_MAN3DIR)/Devel::PerlySense::Document::Api::Method.$(MAN3EXT) \
	  lib/Devel/PerlySense/Document/Location.pm $(INST_MAN3DIR)/Devel::PerlySense::Document::Location.$(MAN3EXT) \
	  lib/Devel/PerlySense/Document/Meta.pm $(INST_MAN3DIR)/Devel::PerlySense::Document::Meta.$(MAN3EXT) \
	  lib/Devel/PerlySense/Editor.pm $(INST_MAN3DIR)/Devel::PerlySense::Editor.$(MAN3EXT) \
	  lib/Devel/PerlySense/Editor/Emacs.pm $(INST_MAN3DIR)/Devel::PerlySense::Editor::Emacs.$(MAN3EXT) \
	  lib/Devel/PerlySense/Editor/Vim.pm $(INST_MAN3DIR)/Devel::PerlySense::Editor::Vim.$(MAN3EXT) \
	  lib/Devel/PerlySense/Home.pm $(INST_MAN3DIR)/Devel::PerlySense::Home.$(MAN3EXT) \
	  lib/Devel/PerlySense/Plugin/Syntax/Moose.pm $(INST_MAN3DIR)/Devel::PerlySense::Plugin::Syntax::Moose.$(MAN3EXT) \
	  lib/Devel/PerlySense/Project.pm $(INST_MAN3DIR)/Devel::PerlySense::Project.$(MAN3EXT) \
	  lib/Devel/PerlySense/Project/Unknown.pm $(INST_MAN3DIR)/Devel::PerlySense::Project::Unknown.$(MAN3EXT) \
	  lib/Devel/PerlySense/Util.pm $(INST_MAN3DIR)/Devel::PerlySense::Util.$(MAN3EXT) \
	  lib/Devel/PerlySense/Util/Log.pm $(INST_MAN3DIR)/Devel::PerlySense::Util::Log.$(MAN3EXT) \
	  lib/Devel/TimeThis.pm $(INST_MAN3DIR)/Devel::TimeThis.$(MAN3EXT) 




# --- MakeMaker processPL section:


# --- MakeMaker installbin section:

EXE_FILES = bin/perly_sense

pure_all :: $(INST_SCRIPT)/perly_sense
	$(NOECHO) $(NOOP)

realclean ::
	$(RM_F) \
	  $(INST_SCRIPT)/perly_sense 

$(INST_SCRIPT)/perly_sense : bin/perly_sense $(FIRST_MAKEFILE) $(INST_SCRIPT)$(DFSEP).exists $(INST_BIN)$(DFSEP).exists
	$(NOECHO) $(RM_F) $(INST_SCRIPT)/perly_sense
	$(CP) bin/perly_sense $(INST_SCRIPT)/perly_sense
	$(FIXIN) $(INST_SCRIPT)/perly_sense
	-$(NOECHO) $(CHMOD) $(PERM_RWX) $(INST_SCRIPT)/perly_sense



# --- MakeMaker subdirs section:

# none

# --- MakeMaker clean_subdirs section:
clean_subdirs :
	$(NOECHO) $(NOOP)


# --- MakeMaker clean section:

# Delete temporary files but do not touch installed files. We don't delete
# the Makefile here so a later make realclean still has a makefile to use.

clean :: clean_subdirs
	- $(RM_F) \
	  $(BASEEXT).bso $(BASEEXT).def \
	  $(BASEEXT).exp $(BASEEXT).x \
	  $(BOOTSTRAP) $(INST_ARCHAUTODIR)/extralibs.all \
	  $(INST_ARCHAUTODIR)/extralibs.ld $(MAKE_APERL_FILE) \
	  *$(LIB_EXT) *$(OBJ_EXT) \
	  *perl.core MYMETA.json \
	  MYMETA.yml blibdirs.ts \
	  core core.*perl.*.? \
	  core.[0-9] core.[0-9][0-9] \
	  core.[0-9][0-9][0-9] core.[0-9][0-9][0-9][0-9] \
	  core.[0-9][0-9][0-9][0-9][0-9] lib$(BASEEXT).def \
	  mon.out perl \
	  perl$(EXE_EXT) perl.exe \
	  perlmain.c pm_to_blib \
	  pm_to_blib.ts so_locations \
	  tmon.out 
	- $(RM_RF) \
	  blib 
	  $(NOECHO) $(RM_F) $(MAKEFILE_OLD)
	- $(MV) $(FIRST_MAKEFILE) $(MAKEFILE_OLD) $(DEV_NULL)


# --- MakeMaker realclean_subdirs section:
# so clean is forced to complete before realclean_subdirs runs
realclean_subdirs : clean
	$(NOECHO) $(NOOP)


# --- MakeMaker realclean section:
# Delete temporary files (via clean) and also delete dist files
realclean purge :: realclean_subdirs
	- $(RM_F) \
	  $(FIRST_MAKEFILE) $(MAKEFILE_OLD) 
	- $(RM_RF) \
	  $(DISTVNAME) 


# --- MakeMaker metafile section:
metafile : create_distdir
	$(NOECHO) $(ECHO) Generating META.yml
	$(NOECHO) $(ECHO) '---' > META_new.yml
	$(NOECHO) $(ECHO) 'abstract: '\''Perl IDE backend with Emacs frontend'\''' >> META_new.yml
	$(NOECHO) $(ECHO) 'author:' >> META_new.yml
	$(NOECHO) $(ECHO) '  - '\''Johan Lindstrom <johanl@cpan.org>'\''' >> META_new.yml
	$(NOECHO) $(ECHO) 'build_requires:' >> META_new.yml
	$(NOECHO) $(ECHO) '  Class::MethodMaker: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Exception::Class: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  ExtUtils::MakeMaker: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::Spec: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::Temp: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Test::Differences: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Test::Exception: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Test::More: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) 'configure_requires:' >> META_new.yml
	$(NOECHO) $(ECHO) '  ExtUtils::MakeMaker: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) 'dynamic_config: 1' >> META_new.yml
	$(NOECHO) $(ECHO) 'generated_by: '\''ExtUtils::MakeMaker version 7.34, CPAN::Meta::Converter version 2.150010'\''' >> META_new.yml
	$(NOECHO) $(ECHO) 'license: perl' >> META_new.yml
	$(NOECHO) $(ECHO) 'meta-spec:' >> META_new.yml
	$(NOECHO) $(ECHO) '  url: http://module-build.sourceforge.net/META-spec-v1.4.html' >> META_new.yml
	$(NOECHO) $(ECHO) '  version: '\''1.4'\''' >> META_new.yml
	$(NOECHO) $(ECHO) 'name: Devel-PerlySense' >> META_new.yml
	$(NOECHO) $(ECHO) 'no_index:' >> META_new.yml
	$(NOECHO) $(ECHO) '  directory:' >> META_new.yml
	$(NOECHO) $(ECHO) '    - t' >> META_new.yml
	$(NOECHO) $(ECHO) '    - inc' >> META_new.yml
	$(NOECHO) $(ECHO) 'requires:' >> META_new.yml
	$(NOECHO) $(ECHO) '  App::Ack: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Cache::Cache: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Cache::FileCache: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Carp: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Cwd: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Data::Dumper: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Digest::SHA: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Exporter: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::Basename: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::Find: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::Find::Rule: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::Path: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::Slurp: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::Spec::Functions: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  File::chdir: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Getopt::Long: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Graph::Easy: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  HTTP::Date: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  IO::String: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  List::AllUtils: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  List::MoreUtils: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  List::Util: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Module::Pluggable: '\''3.5'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Module::Runtime: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Moo: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  POSIX: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  PPI: '\''1.003'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  PPI::Document: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  PPI::Dumper: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Params::Util: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Path::Class: '\''0.11'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Path::Tiny: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Perl::Critic: '\''1.105'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Perl::Tidy: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Pod::Text: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Pod::Usage: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Spiffy: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Storable: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Sub::Exporter: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Text::Table: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Time::HiRes: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  Tree::Parser: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  YAML::Tiny: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  base: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  lib: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  strict: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  utf8: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) '  warnings: '\''0'\''' >> META_new.yml
	$(NOECHO) $(ECHO) 'version: '\''0.0222'\''' >> META_new.yml
	$(NOECHO) $(ECHO) 'x_serialization_backend: '\''CPAN::Meta::YAML version 0.018'\''' >> META_new.yml
	-$(NOECHO) $(MV) META_new.yml $(DISTVNAME)/META.yml
	$(NOECHO) $(ECHO) Generating META.json
	$(NOECHO) $(ECHO) '{' > META_new.json
	$(NOECHO) $(ECHO) '   "abstract" : "Perl IDE backend with Emacs frontend",' >> META_new.json
	$(NOECHO) $(ECHO) '   "author" : [' >> META_new.json
	$(NOECHO) $(ECHO) '      "Johan Lindstrom <johanl@cpan.org>"' >> META_new.json
	$(NOECHO) $(ECHO) '   ],' >> META_new.json
	$(NOECHO) $(ECHO) '   "dynamic_config" : 1,' >> META_new.json
	$(NOECHO) $(ECHO) '   "generated_by" : "ExtUtils::MakeMaker version 7.34, CPAN::Meta::Converter version 2.150010",' >> META_new.json
	$(NOECHO) $(ECHO) '   "license" : [' >> META_new.json
	$(NOECHO) $(ECHO) '      "perl_5"' >> META_new.json
	$(NOECHO) $(ECHO) '   ],' >> META_new.json
	$(NOECHO) $(ECHO) '   "meta-spec" : {' >> META_new.json
	$(NOECHO) $(ECHO) '      "url" : "http://search.cpan.org/perldoc?CPAN::Meta::Spec",' >> META_new.json
	$(NOECHO) $(ECHO) '      "version" : 2' >> META_new.json
	$(NOECHO) $(ECHO) '   },' >> META_new.json
	$(NOECHO) $(ECHO) '   "name" : "Devel-PerlySense",' >> META_new.json
	$(NOECHO) $(ECHO) '   "no_index" : {' >> META_new.json
	$(NOECHO) $(ECHO) '      "directory" : [' >> META_new.json
	$(NOECHO) $(ECHO) '         "t",' >> META_new.json
	$(NOECHO) $(ECHO) '         "inc"' >> META_new.json
	$(NOECHO) $(ECHO) '      ]' >> META_new.json
	$(NOECHO) $(ECHO) '   },' >> META_new.json
	$(NOECHO) $(ECHO) '   "prereqs" : {' >> META_new.json
	$(NOECHO) $(ECHO) '      "build" : {' >> META_new.json
	$(NOECHO) $(ECHO) '         "requires" : {' >> META_new.json
	$(NOECHO) $(ECHO) '            "ExtUtils::MakeMaker" : "0"' >> META_new.json
	$(NOECHO) $(ECHO) '         }' >> META_new.json
	$(NOECHO) $(ECHO) '      },' >> META_new.json
	$(NOECHO) $(ECHO) '      "configure" : {' >> META_new.json
	$(NOECHO) $(ECHO) '         "requires" : {' >> META_new.json
	$(NOECHO) $(ECHO) '            "ExtUtils::MakeMaker" : "0"' >> META_new.json
	$(NOECHO) $(ECHO) '         }' >> META_new.json
	$(NOECHO) $(ECHO) '      },' >> META_new.json
	$(NOECHO) $(ECHO) '      "runtime" : {' >> META_new.json
	$(NOECHO) $(ECHO) '         "requires" : {' >> META_new.json
	$(NOECHO) $(ECHO) '            "App::Ack" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Cache::Cache" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Cache::FileCache" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Carp" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Cwd" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Data::Dumper" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Digest::SHA" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Exporter" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::Basename" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::Find" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::Find::Rule" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::Path" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::Slurp" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::Spec::Functions" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::chdir" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Getopt::Long" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Graph::Easy" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "HTTP::Date" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "IO::String" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "List::AllUtils" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "List::MoreUtils" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "List::Util" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Module::Pluggable" : "3.5",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Module::Runtime" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Moo" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "POSIX" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "PPI" : "1.003",' >> META_new.json
	$(NOECHO) $(ECHO) '            "PPI::Document" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "PPI::Dumper" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Params::Util" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Path::Class" : "0.11",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Path::Tiny" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Perl::Critic" : "1.105",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Perl::Tidy" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Pod::Text" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Pod::Usage" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Spiffy" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Storable" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Sub::Exporter" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Text::Table" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Time::HiRes" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Tree::Parser" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "YAML::Tiny" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "base" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "lib" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "strict" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "utf8" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "warnings" : "0"' >> META_new.json
	$(NOECHO) $(ECHO) '         }' >> META_new.json
	$(NOECHO) $(ECHO) '      },' >> META_new.json
	$(NOECHO) $(ECHO) '      "test" : {' >> META_new.json
	$(NOECHO) $(ECHO) '         "requires" : {' >> META_new.json
	$(NOECHO) $(ECHO) '            "Class::MethodMaker" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Exception::Class" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::Spec" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "File::Temp" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Test::Differences" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Test::Exception" : "0",' >> META_new.json
	$(NOECHO) $(ECHO) '            "Test::More" : "0"' >> META_new.json
	$(NOECHO) $(ECHO) '         }' >> META_new.json
	$(NOECHO) $(ECHO) '      }' >> META_new.json
	$(NOECHO) $(ECHO) '   },' >> META_new.json
	$(NOECHO) $(ECHO) '   "release_status" : "stable",' >> META_new.json
	$(NOECHO) $(ECHO) '   "version" : "0.0222",' >> META_new.json
	$(NOECHO) $(ECHO) '   "x_serialization_backend" : "JSON::PP version 2.97001"' >> META_new.json
	$(NOECHO) $(ECHO) '}' >> META_new.json
	-$(NOECHO) $(MV) META_new.json $(DISTVNAME)/META.json


# --- MakeMaker signature section:
signature :
	cpansign -s


# --- MakeMaker dist_basics section:
distclean :: realclean distcheck
	$(NOECHO) $(NOOP)

distcheck :
	$(PERLRUN) "-MExtUtils::Manifest=fullcheck" -e fullcheck

skipcheck :
	$(PERLRUN) "-MExtUtils::Manifest=skipcheck" -e skipcheck

manifest :
	$(PERLRUN) "-MExtUtils::Manifest=mkmanifest" -e mkmanifest

veryclean : realclean
	$(RM_F) *~ */*~ *.orig */*.orig *.bak */*.bak *.old */*.old



# --- MakeMaker dist_core section:

dist : $(DIST_DEFAULT) $(FIRST_MAKEFILE)
	$(NOECHO) $(ABSPERLRUN) -l -e 'print '\''Warning: Makefile possibly out of date with $(VERSION_FROM)'\''' \
	  -e '    if -e '\''$(VERSION_FROM)'\'' and -M '\''$(VERSION_FROM)'\'' < -M '\''$(FIRST_MAKEFILE)'\'';' --

tardist : $(DISTVNAME).tar$(SUFFIX)
	$(NOECHO) $(NOOP)

uutardist : $(DISTVNAME).tar$(SUFFIX)
	uuencode $(DISTVNAME).tar$(SUFFIX) $(DISTVNAME).tar$(SUFFIX) > $(DISTVNAME).tar$(SUFFIX)_uu
	$(NOECHO) $(ECHO) 'Created $(DISTVNAME).tar$(SUFFIX)_uu'

$(DISTVNAME).tar$(SUFFIX) : distdir
	$(PREOP)
	$(TO_UNIX)
	$(TAR) $(TARFLAGS) $(DISTVNAME).tar $(DISTVNAME)
	$(RM_RF) $(DISTVNAME)
	$(COMPRESS) $(DISTVNAME).tar
	$(NOECHO) $(ECHO) 'Created $(DISTVNAME).tar$(SUFFIX)'
	$(POSTOP)

zipdist : $(DISTVNAME).zip
	$(NOECHO) $(NOOP)

$(DISTVNAME).zip : distdir
	$(PREOP)
	$(ZIP) $(ZIPFLAGS) $(DISTVNAME).zip $(DISTVNAME)
	$(RM_RF) $(DISTVNAME)
	$(NOECHO) $(ECHO) 'Created $(DISTVNAME).zip'
	$(POSTOP)

shdist : distdir
	$(PREOP)
	$(SHAR) $(DISTVNAME) > $(DISTVNAME).shar
	$(RM_RF) $(DISTVNAME)
	$(NOECHO) $(ECHO) 'Created $(DISTVNAME).shar'
	$(POSTOP)


# --- MakeMaker distdir section:
create_distdir :
	$(RM_RF) $(DISTVNAME)
	$(PERLRUN) "-MExtUtils::Manifest=manicopy,maniread" \
		-e "manicopy(maniread(),'$(DISTVNAME)', '$(DIST_CP)');"

distdir : create_distdir distmeta 
	$(NOECHO) $(NOOP)



# --- MakeMaker dist_test section:
disttest : distdir
	cd $(DISTVNAME) && $(ABSPERLRUN) Makefile.PL 
	cd $(DISTVNAME) && $(MAKE) $(PASTHRU)
	cd $(DISTVNAME) && $(MAKE) test $(PASTHRU)



# --- MakeMaker dist_ci section:
ci :
	$(ABSPERLRUN) -MExtUtils::Manifest=maniread -e '@all = sort keys %{ maniread() };' \
	  -e 'print(qq{Executing $(CI) @all\n});' \
	  -e 'system(qq{$(CI) @all}) == 0 or die $$!;' \
	  -e 'print(qq{Executing $(RCS_LABEL) ...\n});' \
	  -e 'system(qq{$(RCS_LABEL) @all}) == 0 or die $$!;' --


# --- MakeMaker distmeta section:
distmeta : create_distdir metafile
	$(NOECHO) cd $(DISTVNAME) && $(ABSPERLRUN) -MExtUtils::Manifest=maniadd -e 'exit unless -e q{META.yml};' \
	  -e 'eval { maniadd({q{META.yml} => q{Module YAML meta-data (added by MakeMaker)}}) }' \
	  -e '    or die "Could not add META.yml to MANIFEST: $${'\''@'\''}"' --
	$(NOECHO) cd $(DISTVNAME) && $(ABSPERLRUN) -MExtUtils::Manifest=maniadd -e 'exit unless -f q{META.json};' \
	  -e 'eval { maniadd({q{META.json} => q{Module JSON meta-data (added by MakeMaker)}}) }' \
	  -e '    or die "Could not add META.json to MANIFEST: $${'\''@'\''}"' --



# --- MakeMaker distsignature section:
distsignature : distmeta
	$(NOECHO) cd $(DISTVNAME) && $(ABSPERLRUN) -MExtUtils::Manifest=maniadd -e 'eval { maniadd({q{SIGNATURE} => q{Public-key signature (added by MakeMaker)}}) }' \
	  -e '    or die "Could not add SIGNATURE to MANIFEST: $${'\''@'\''}"' --
	$(NOECHO) cd $(DISTVNAME) && $(TOUCH) SIGNATURE
	cd $(DISTVNAME) && cpansign -s



# --- MakeMaker install section:

install :: pure_install doc_install
	$(NOECHO) $(NOOP)

install_perl :: pure_perl_install doc_perl_install
	$(NOECHO) $(NOOP)

install_site :: pure_site_install doc_site_install
	$(NOECHO) $(NOOP)

install_vendor :: pure_vendor_install doc_vendor_install
	$(NOECHO) $(NOOP)

pure_install :: pure_$(INSTALLDIRS)_install
	$(NOECHO) $(NOOP)

doc_install :: doc_$(INSTALLDIRS)_install
	$(NOECHO) $(NOOP)

pure__install : pure_site_install
	$(NOECHO) $(ECHO) INSTALLDIRS not defined, defaulting to INSTALLDIRS=site

doc__install : doc_site_install
	$(NOECHO) $(ECHO) INSTALLDIRS not defined, defaulting to INSTALLDIRS=site

pure_perl_install :: all
	$(NOECHO) $(MOD_INSTALL) \
		read "$(PERL_ARCHLIB)/auto/$(FULLEXT)/.packlist" \
		write "$(DESTINSTALLARCHLIB)/auto/$(FULLEXT)/.packlist" \
		"$(INST_LIB)" "$(DESTINSTALLPRIVLIB)" \
		"$(INST_ARCHLIB)" "$(DESTINSTALLARCHLIB)" \
		"$(INST_BIN)" "$(DESTINSTALLBIN)" \
		"$(INST_SCRIPT)" "$(DESTINSTALLSCRIPT)" \
		"$(INST_MAN1DIR)" "$(DESTINSTALLMAN1DIR)" \
		"$(INST_MAN3DIR)" "$(DESTINSTALLMAN3DIR)"
	$(NOECHO) $(WARN_IF_OLD_PACKLIST) \
		"$(SITEARCHEXP)/auto/$(FULLEXT)"


pure_site_install :: all
	$(NOECHO) $(MOD_INSTALL) \
		read "$(SITEARCHEXP)/auto/$(FULLEXT)/.packlist" \
		write "$(DESTINSTALLSITEARCH)/auto/$(FULLEXT)/.packlist" \
		"$(INST_LIB)" "$(DESTINSTALLSITELIB)" \
		"$(INST_ARCHLIB)" "$(DESTINSTALLSITEARCH)" \
		"$(INST_BIN)" "$(DESTINSTALLSITEBIN)" \
		"$(INST_SCRIPT)" "$(DESTINSTALLSITESCRIPT)" \
		"$(INST_MAN1DIR)" "$(DESTINSTALLSITEMAN1DIR)" \
		"$(INST_MAN3DIR)" "$(DESTINSTALLSITEMAN3DIR)"
	$(NOECHO) $(WARN_IF_OLD_PACKLIST) \
		"$(PERL_ARCHLIB)/auto/$(FULLEXT)"

pure_vendor_install :: all
	$(NOECHO) $(MOD_INSTALL) \
		read "$(VENDORARCHEXP)/auto/$(FULLEXT)/.packlist" \
		write "$(DESTINSTALLVENDORARCH)/auto/$(FULLEXT)/.packlist" \
		"$(INST_LIB)" "$(DESTINSTALLVENDORLIB)" \
		"$(INST_ARCHLIB)" "$(DESTINSTALLVENDORARCH)" \
		"$(INST_BIN)" "$(DESTINSTALLVENDORBIN)" \
		"$(INST_SCRIPT)" "$(DESTINSTALLVENDORSCRIPT)" \
		"$(INST_MAN1DIR)" "$(DESTINSTALLVENDORMAN1DIR)" \
		"$(INST_MAN3DIR)" "$(DESTINSTALLVENDORMAN3DIR)"


doc_perl_install :: all
	$(NOECHO) $(ECHO) Appending installation info to "$(DESTINSTALLARCHLIB)/perllocal.pod"
	-$(NOECHO) $(MKPATH) "$(DESTINSTALLARCHLIB)"
	-$(NOECHO) $(DOC_INSTALL) \
		"Module" "$(NAME)" \
		"installed into" "$(INSTALLPRIVLIB)" \
		LINKTYPE "$(LINKTYPE)" \
		VERSION "$(VERSION)" \
		EXE_FILES "$(EXE_FILES)" \
		>> "$(DESTINSTALLARCHLIB)/perllocal.pod"

doc_site_install :: all
	$(NOECHO) $(ECHO) Appending installation info to "$(DESTINSTALLARCHLIB)/perllocal.pod"
	-$(NOECHO) $(MKPATH) "$(DESTINSTALLARCHLIB)"
	-$(NOECHO) $(DOC_INSTALL) \
		"Module" "$(NAME)" \
		"installed into" "$(INSTALLSITELIB)" \
		LINKTYPE "$(LINKTYPE)" \
		VERSION "$(VERSION)" \
		EXE_FILES "$(EXE_FILES)" \
		>> "$(DESTINSTALLARCHLIB)/perllocal.pod"

doc_vendor_install :: all
	$(NOECHO) $(ECHO) Appending installation info to "$(DESTINSTALLARCHLIB)/perllocal.pod"
	-$(NOECHO) $(MKPATH) "$(DESTINSTALLARCHLIB)"
	-$(NOECHO) $(DOC_INSTALL) \
		"Module" "$(NAME)" \
		"installed into" "$(INSTALLVENDORLIB)" \
		LINKTYPE "$(LINKTYPE)" \
		VERSION "$(VERSION)" \
		EXE_FILES "$(EXE_FILES)" \
		>> "$(DESTINSTALLARCHLIB)/perllocal.pod"


uninstall :: uninstall_from_$(INSTALLDIRS)dirs
	$(NOECHO) $(NOOP)

uninstall_from_perldirs ::
	$(NOECHO) $(UNINSTALL) "$(PERL_ARCHLIB)/auto/$(FULLEXT)/.packlist"

uninstall_from_sitedirs ::
	$(NOECHO) $(UNINSTALL) "$(SITEARCHEXP)/auto/$(FULLEXT)/.packlist"

uninstall_from_vendordirs ::
	$(NOECHO) $(UNINSTALL) "$(VENDORARCHEXP)/auto/$(FULLEXT)/.packlist"


# --- MakeMaker force section:
# Phony target to force checking subdirectories.
FORCE :
	$(NOECHO) $(NOOP)


# --- MakeMaker perldepend section:


# --- MakeMaker makefile section:
# We take a very conservative approach here, but it's worth it.
# We move Makefile to Makefile.old here to avoid gnu make looping.
$(FIRST_MAKEFILE) : Makefile.PL $(CONFIGDEP)
	$(NOECHO) $(ECHO) "Makefile out-of-date with respect to $?"
	$(NOECHO) $(ECHO) "Cleaning current config before rebuilding Makefile..."
	-$(NOECHO) $(RM_F) $(MAKEFILE_OLD)
	-$(NOECHO) $(MV)   $(FIRST_MAKEFILE) $(MAKEFILE_OLD)
	- $(MAKE) $(USEMAKEFILE) $(MAKEFILE_OLD) clean $(DEV_NULL)
	$(PERLRUN) Makefile.PL 
	$(NOECHO) $(ECHO) "==> Your Makefile has been rebuilt. <=="
	$(NOECHO) $(ECHO) "==> Please rerun the $(MAKE) command.  <=="
	$(FALSE)



# --- MakeMaker staticmake section:

# --- MakeMaker makeaperl section ---
MAP_TARGET    = perl
FULLPERL      = "/usr/bin/perl"
MAP_PERLINC   = "-Iblib/arch" "-Iblib/lib" "-I/usr/lib64/perl5" "-I/usr/share/perl5"

$(MAP_TARGET) :: $(MAKE_APERL_FILE)
	$(MAKE) $(USEMAKEFILE) $(MAKE_APERL_FILE) $@

$(MAKE_APERL_FILE) : static $(FIRST_MAKEFILE) pm_to_blib
	$(NOECHO) $(ECHO) Writing \"$(MAKE_APERL_FILE)\" for this $(MAP_TARGET)
	$(NOECHO) $(PERLRUNINST) \
		Makefile.PL DIR="" \
		MAKEFILE=$(MAKE_APERL_FILE) LINKTYPE=static \
		MAKEAPERL=1 NORECURS=1 CCCDLFLAGS=


# --- MakeMaker test section:
TEST_VERBOSE=0
TEST_TYPE=test_$(LINKTYPE)
TEST_FILE = test.pl
TEST_FILES = t/*.t t/data/project/with-dir/source/t/*.t t/data/project/with-git/source/bogus/t/*.t t/data/project/with-perlysenseproject/source/bogus/t/*.t
TESTDB_SW = -d

testdb :: testdb_$(LINKTYPE)
	$(NOECHO) $(NOOP)

test :: $(TEST_TYPE)
	$(NOECHO) $(NOOP)

# Occasionally we may face this degenerate target:
test_ : test_dynamic
	$(NOECHO) $(NOOP)

subdirs-test_dynamic :: dynamic pure_all

test_dynamic :: subdirs-test_dynamic
	PERL_DL_NONLAZY=1 $(FULLPERLRUN) "-MExtUtils::Command::MM" "-MTest::Harness" "-e" "undef *Test::Harness::Switches; test_harness($(TEST_VERBOSE), '$(INST_LIB)', '$(INST_ARCHLIB)')" $(TEST_FILES)

testdb_dynamic :: dynamic pure_all
	PERL_DL_NONLAZY=1 $(FULLPERLRUN) $(TESTDB_SW) "-I$(INST_LIB)" "-I$(INST_ARCHLIB)" $(TEST_FILE)

subdirs-test_static :: static pure_all

test_static :: subdirs-test_static
	PERL_DL_NONLAZY=1 $(FULLPERLRUN) "-MExtUtils::Command::MM" "-MTest::Harness" "-e" "undef *Test::Harness::Switches; test_harness($(TEST_VERBOSE), '$(INST_LIB)', '$(INST_ARCHLIB)')" $(TEST_FILES)

testdb_static :: static pure_all
	PERL_DL_NONLAZY=1 $(FULLPERLRUN) $(TESTDB_SW) "-I$(INST_LIB)" "-I$(INST_ARCHLIB)" $(TEST_FILE)



# --- MakeMaker ppd section:
# Creates a PPD (Perl Package Description) for a binary distribution.
ppd :
	$(NOECHO) $(ECHO) '<SOFTPKG NAME="Devel-PerlySense" VERSION="0.0222">' > Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '    <ABSTRACT>Perl IDE backend with Emacs frontend</ABSTRACT>' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '    <AUTHOR>Johan Lindstrom &lt;johanl@cpan.org&gt;</AUTHOR>' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '    <IMPLEMENTATION>' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="App::Ack" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Cache::Cache" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Cache::FileCache" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Carp::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Cwd::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Data::Dumper" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Digest::SHA" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Exporter::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="File::Basename" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="File::Find" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="File::Find::Rule" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="File::Path" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="File::Slurp" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="File::Spec::Functions" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="File::chdir" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Getopt::Long" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Graph::Easy" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="HTTP::Date" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="IO::String" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="List::AllUtils" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="List::MoreUtils" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="List::Util" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Module::Pluggable" VERSION="3.5" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Module::Runtime" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Moo::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="POSIX::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="PPI::" VERSION="1.003" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="PPI::Document" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="PPI::Dumper" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Params::Util" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Path::Class" VERSION="0.11" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Path::Tiny" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Perl::Critic" VERSION="1.105" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Perl::Tidy" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Pod::Text" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Pod::Usage" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Spiffy::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Storable::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Sub::Exporter" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Text::Table" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Time::HiRes" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="Tree::Parser" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="YAML::Tiny" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="base::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="lib::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="strict::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="utf8::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <REQUIRE NAME="warnings::" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <ARCHITECTURE NAME="x86_64-linux-thread-multi-5.26" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '        <CODEBASE HREF="" />' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '    </IMPLEMENTATION>' >> Devel-PerlySense.ppd
	$(NOECHO) $(ECHO) '</SOFTPKG>' >> Devel-PerlySense.ppd


# --- MakeMaker pm_to_blib section:

pm_to_blib : $(FIRST_MAKEFILE) $(TO_INST_PM)
	$(NOECHO) $(ABSPERLRUN) -MExtUtils::Install -e 'pm_to_blib({@ARGV}, '\''$(INST_LIB)/auto'\'', q[$(PM_FILTER)], '\''$(PERM_DIR)'\'')' -- \
	  'lib/Devel/PerlySense.pm' 'blib/lib/Devel/PerlySense.pm' \
	  'lib/Devel/PerlySense/Bookmark/Definition.pm' 'blib/lib/Devel/PerlySense/Bookmark/Definition.pm' \
	  'lib/Devel/PerlySense/Bookmark/Match.pm' 'blib/lib/Devel/PerlySense/Bookmark/Match.pm' \
	  'lib/Devel/PerlySense/Bookmark/MatchResult.pm' 'blib/lib/Devel/PerlySense/Bookmark/MatchResult.pm' \
	  'lib/Devel/PerlySense/BookmarkConfig.pm' 'blib/lib/Devel/PerlySense/BookmarkConfig.pm' \
	  'lib/Devel/PerlySense/CallTree.pm' 'blib/lib/Devel/PerlySense/CallTree.pm' \
	  'lib/Devel/PerlySense/CallTree/Caller.pm' 'blib/lib/Devel/PerlySense/CallTree/Caller.pm' \
	  'lib/Devel/PerlySense/CallTree/Graph.pm' 'blib/lib/Devel/PerlySense/CallTree/Graph.pm' \
	  'lib/Devel/PerlySense/Class.pm' 'blib/lib/Devel/PerlySense/Class.pm' \
	  'lib/Devel/PerlySense/Config/Project.pm' 'blib/lib/Devel/PerlySense/Config/Project.pm' \
	  'lib/Devel/PerlySense/Config/Project/Default.pm' 'blib/lib/Devel/PerlySense/Config/Project/Default.pm' \
	  'lib/Devel/PerlySense/Cookbook.pod' 'blib/lib/Devel/PerlySense/Cookbook.pod' \
	  'lib/Devel/PerlySense/Document.pm' 'blib/lib/Devel/PerlySense/Document.pm' \
	  'lib/Devel/PerlySense/Document/Api.pm' 'blib/lib/Devel/PerlySense/Document/Api.pm' \
	  'lib/Devel/PerlySense/Document/Api/Method.pm' 'blib/lib/Devel/PerlySense/Document/Api/Method.pm' \
	  'lib/Devel/PerlySense/Document/Location.pm' 'blib/lib/Devel/PerlySense/Document/Location.pm' \
	  'lib/Devel/PerlySense/Document/Meta.pm' 'blib/lib/Devel/PerlySense/Document/Meta.pm' \
	  'lib/Devel/PerlySense/Editor.pm' 'blib/lib/Devel/PerlySense/Editor.pm' \
	  'lib/Devel/PerlySense/Editor/Emacs.pm' 'blib/lib/Devel/PerlySense/Editor/Emacs.pm' \
	  'lib/Devel/PerlySense/Editor/Vim.pm' 'blib/lib/Devel/PerlySense/Editor/Vim.pm' \
	  'lib/Devel/PerlySense/Home.pm' 'blib/lib/Devel/PerlySense/Home.pm' \
	  'lib/Devel/PerlySense/Plugin/Syntax/Moose.pm' 'blib/lib/Devel/PerlySense/Plugin/Syntax/Moose.pm' \
	  'lib/Devel/PerlySense/Project.pm' 'blib/lib/Devel/PerlySense/Project.pm' \
	  'lib/Devel/PerlySense/Project/Unknown.pm' 'blib/lib/Devel/PerlySense/Project/Unknown.pm' \
	  'lib/Devel/PerlySense/Util.pm' 'blib/lib/Devel/PerlySense/Util.pm' \
	  'lib/Devel/PerlySense/Util/Log.pm' 'blib/lib/Devel/PerlySense/Util/Log.pm' \
	  'lib/Devel/PerlySense/external/emacs/async-shell-command-to-string.el' 'blib/lib/Devel/PerlySense/external/emacs/async-shell-command-to-string.el' \
	  'lib/Devel/PerlySense/external/emacs/dropdown-list.el' 'blib/lib/Devel/PerlySense/external/emacs/dropdown-list.el' \
	  'lib/Devel/PerlySense/external/emacs/lib/lang-refactor-perl.el' 'blib/lib/Devel/PerlySense/external/emacs/lib/lang-refactor-perl.el' 
	$(NOECHO) $(ABSPERLRUN) -MExtUtils::Install -e 'pm_to_blib({@ARGV}, '\''$(INST_LIB)/auto'\'', q[$(PM_FILTER)], '\''$(PERM_DIR)'\'')' -- \
	  'lib/Devel/PerlySense/external/emacs/perly-sense-flymake.el' 'blib/lib/Devel/PerlySense/external/emacs/perly-sense-flymake.el' \
	  'lib/Devel/PerlySense/external/emacs/perly-sense-test-class.el' 'blib/lib/Devel/PerlySense/external/emacs/perly-sense-test-class.el' \
	  'lib/Devel/PerlySense/external/emacs/perly-sense-visualize-coverage.el' 'blib/lib/Devel/PerlySense/external/emacs/perly-sense-visualize-coverage.el' \
	  'lib/Devel/PerlySense/external/emacs/perly-sense.el' 'blib/lib/Devel/PerlySense/external/emacs/perly-sense.el' \
	  'lib/Devel/PerlySense/external/emacs/regex-tool.el' 'blib/lib/Devel/PerlySense/external/emacs/regex-tool.el' \
	  'lib/Devel/PerlySense/external/emacs/shell-command-pool.el' 'blib/lib/Devel/PerlySense/external/emacs/shell-command-pool.el' \
	  'lib/Devel/TimeThis.pm' 'blib/lib/Devel/TimeThis.pm' 
	$(NOECHO) $(TOUCH) pm_to_blib


# --- MakeMaker selfdocument section:

# here so even if top_targets is overridden, these will still be defined
# gmake will silently still work if any are .PHONY-ed but nmake won't

static ::
	$(NOECHO) $(NOOP)

dynamic ::
	$(NOECHO) $(NOOP)

config ::
	$(NOECHO) $(NOOP)


# --- MakeMaker postamble section:


# End.
