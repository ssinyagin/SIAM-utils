
SUBST = @abs_top_builddir@/setup_tools/substvars.sh

bin_SCRIPTS = \
	siam_search

CLEANFILES = $(bin_SCRIPTS)

EXTRA_DIST = \
	siam_search.in


siam_search: siam_search.in
	$(SUBST) siam_search.in > siam_search
