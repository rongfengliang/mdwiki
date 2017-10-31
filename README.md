[![Build Status](https://travis-ci.org/Dynalon/mdwiki.png?branch=master)](https://travis-ci.org/Dynalon/mdwiki)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Frongfengliang%2Fmdwiki.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Frongfengliang%2Fmdwiki?ref=badge_shield)


MDwiki
======

100% static single file CMS/Wiki done purely with client-side Javascript and HTML5.

See http://www.mdwiki.info for more info and documentation.
------


Download
--------

See <https://github.com/Dynalon/mdwiki/releases> for readily precompiled releases.

How to build from source
------------------------
(applies to master branch, stable may differ)

1. Install node.js >= 0.10 and npm (if not included)
2. Clone the mdwiki repo
3. Install deps and build MDwiki (you need automake installed - if you are on Windows check the contents of the Makefile for the list of commands to run them manually):

```
    make
```

4. Find the `mdwiki.html` in the `dist/` folder

5. Development

For development, use

    grunt devel 

To get unminified source code compiled to `dist/mdwiki-debug.html`, as well as auto file watching and livereload support. Symlink the development mdwiki file into your webroot for testing.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/Dynalon/mdwiki/trend.png)](https://bitdeli.com/free "Bitdeli Badge")



## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Frongfengliang%2Fmdwiki.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Frongfengliang%2Fmdwiki?ref=badge_large)