Here are the latest pages from the international sections of www.pmwiki.org.

The files from _ONE_ "wikilib.d" directory should be placed into the
pmwiki/wikilib.d directory on your server.

The UTF-8 encoding can display all languages. It is newer than ISO-8859-*
encodings and is currently not enabled in PmWiki by default. In the future, 
PmWiki will switch to UTF-8 encoding by default, but currently many sites
still use the older encodings.

All international pages for all languages exist in the UTF-8 encoding. For some
languages which were formerly in their older encodings, we provide backwards-
compatible files.

New wiki installations: use the files from the UTF-8 subdirectory.

Existing wiki installations: use the files from the subdirectory that corresponds 
to the encoding of your wiki:
* if we have _only_ UTF-8 files for your language, use them
* for a ISO-* wiki, use the files from the ISO-* subdirectory
* for a UTF-8 wiki, use the files from the UTF-8 subdirectory
* if you don't know what is your encoding, and there is an ISO-* directory, you
  should probably use the files from the ISO-* directory, otherwise from UTF-8

Please report bugs here: http://www.pmwiki.org/wiki/PITS.

Petko Yotov
