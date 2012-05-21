Black Open Pastebin
===================
### v0.0.1 

Edited by schwarzenbart (2012)

Donate (BTC): 15N9ahAiCVHNCJEUF9YA6AEt8Hg5BmnPR6

### Original Author
Copyright (c) 2009-2011 Xan Manning (http://xan-manning.co.uk/)

(Please also tip the original author Bitcoin wallet): 1BFhtdVYmtAuYostpZLDAiGt1dmJaHTRDW 


More Information
----------------

Released under the terms of the MIT License.
See the MIT for details (http://opensource.org/licenses/mit-license.php).

A quick to set up, rapid install, two-file pastebin! (or at least can be) Supports text and image hosting, and url linking. Optimised for Onion Routing

 * EXAMPLE: http://hvieybi6rb45wfpg.onion/

The original code by Xan Manning is very nice and fun, a bit messy to follow, but not very good for run through Tor Browsers. This project aim to expel the javascript (blocked by browser when using tor) and make it lighter for slow tor connection.



CONTENTS
--------

1. Authors / Contributors
2. Features
3. Requirements
4. Installation
5. ToDo
6. Copying


FEATURES
--------

Here is a list of features that this pastebin software boasts.

 * Line Highlighting
 * Syntax Highlighting (with GeSHi, not included)
 * Editing pastes, history.
 * Image hosting
 * Copying images from URLs
 * URL Shortening/redirection
 * Developer API access.
 * Robot Spam protection
 * Paste privacy settings
 * Paste lifespan settings
 * Password Protected/Encrypted Pastes
 * List pastes by Username


AUTHORS/CONTRIBUTORS
--------------------

 * schwarzenbart (no emailing!)
 * Xan Manning (xan[dot]manning[at]gmail[dot]com)
 * Matt Klich https://github.com/elementalvoid
 * Shadow-Majestic https://github.com/shadowmajestic
 * Plytro https://github.com/plytro
 * Moritz Naumann http://moritz-naumann.com



REQUIREMENTS
------------

I test this only on Nginx on Debian Squeeze (like pzt.me). I do not test on other OS or httpd so I cannot express support. You should try it yourself.


INSTALLATION
------------

1. Copy config.php.dist to config.php
2. Change the $CONFIG variables in config.php
3. Upload to your server
4. CHMOD the containing folder to 0777.
5. Visit http://yoursite/path/to/pastebin/index.php
6. Watch it install.
7. CHMOD the containing folder to 0755.
8. Done.


TODO
----

 * Code Tidy, Optimise, remove bloat.
 * Control ID format (Numerical, Alphanumerical, "Random" and Hex)
 * Password Protected and Encrypted Pastes (CURRENTLY IN TESTING BRANCH)
 * List Author Pastes, details of paste. (CURRENTLY IN UNSTABLE BRANCH, UNFORMATTED)
 * Image Thumbnails (Using either GD or ImageMagick)
 * Languages
 * Remove Video stuff...
 * Change the way that Syntax Highlighting stuff is stored (Save disk space)
 * Temporary user paste deletion rights
 * IP Bans
 * XML or JSON API Response


COPYING
-------

Copyright (c) 2009-2011 Xan Manning (http://xan-manning.co.uk)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
