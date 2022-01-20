EXTRA_DIST = \
    Sweetly \
    COPYING \
    AUTHORS \
    README.md

themedir = $(datadir)/themes

install-data-hook:
    $(MKDIR_P) $(DESTDIR)/usr/share/themes
    cp -Rv Sweetly $(DESTDIR)/usr/share/themes/.

uninstall-hook:
    test -e $(DESTDIR)/usr/share/themes/Sweetly && rm -rfv $(DESTDIR)/usr/share/themes/Sweetly