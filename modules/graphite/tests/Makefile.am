modules_graphite_tests_TESTS	= \
	modules/graphite/tests/test_graphite

check_PROGRAMS += ${modules_graphite_tests_TESTS}

modules_graphite_tests_test_graphite_CFLAGS  = $(TEST_CFLAGS)
modules_graphite_tests_test_graphite_LDADD   = $(TEST_LDADD)
modules_graphite_tests_test_graphite_LDFLAGS = \
    $(PREOPEN_SYSLOGFORMAT)       \
    -dlpreopen $(top_builddir)/modules/graphite/libgraphite.la
modules_graphite_tests_test_graphite_DEPENDENCIES = $(top_builddir)/modules/graphite/libgraphite.la
