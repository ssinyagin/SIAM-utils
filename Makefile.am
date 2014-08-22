
SUBDIRS = . bin 

EXTRA_DIST = 


dist-hook:
	date >DIST_REVISION
	git branch -vv >>DIST_REVISION
	cp DIST_REVISION $(distdir)/


