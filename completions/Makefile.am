## Rafael Lee <rafaellee.img@gmail.com>

data_DATA = $(PACKAGE)

install:
	$(mkinstalldirs) $(DESTDIR)$(datadir)/bash-completion/completions/
	$(INSTALL_DATA) $(top_srcdir)/completions/$(PACKAGE) $(DESTDIR)$(datadir)/bash-completion/completions/$(PACKAGE)

uninstall:
	$(DESTDIR)$(datadir)/bash-completion/completions/$(PACKAGE)
