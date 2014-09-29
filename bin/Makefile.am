
SUBST = @abs_top_builddir@/setup_tools/substvars.sh

bin_SCRIPTS = \
	siam_computable \
	siam_search

CLEANFILES = $(bin_SCRIPTS)

EXTRA_DIST = \
	siam_computable.in \
	siam_search.in

siam_computable: siam_computable.in
	$(SUBST) siam_computable.in > siam_computable

siam_search: siam_search.in
	$(SUBST) siam_search.in > siam_search
