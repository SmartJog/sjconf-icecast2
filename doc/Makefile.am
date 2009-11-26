man8_MANS = sjconf-icecast2.man
DISTCLEANFILES = sjconf-icecast2.man
EXTRA_DIST = sjconf-icecast2.t2t

SUFFIXES = .t2t

.t2t.man:
	txt2tags -o $@ $<
