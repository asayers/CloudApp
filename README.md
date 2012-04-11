CloudApp
========

A simple command-line cloudapp client for Linux, OS X, and Windows. It uploads a file to CloudApp and drops the URL into your clipboard.


Installation
-------------

1. Check you have Ruby installed: `ruby --version`
2. Make the script executable: `chmod +x cloudapp`
3. Place it somewhere on your $PATH (/usr/bin/, /usr/local/bin/, or ~/bin/)
4. Store your CloudApp credentials as an entry in ~/.netrc or in ~/.cloudapp.

.netrc:

    machine getcloudapp.com
      logon EMAIL
      password PASSWORD

.cloudapp:

    EMAIL
    PASSWORD

Usage
-------

1. Run `cloudapp FILE`
2. Paste link, either from the clipboard or from the primary.

Licence
-------

> This program is free software: you can redistribute it and/or modify
> it under the terms of the GNU General Public License as published by
> the Free Software Foundation, either version 3 of the License, or
> (at your option) any later version.
>
> This program is distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
> GNU General Public License for more details.
>
> You should have received a copy of the GNU General Public License
> along with this program.  If not, see http://www.gnu.org/licenses/

Authors
-------

 - Zach Holman (@holman) - Original script
 - Aashay Desai (@aashaySFDC) - added support for Windows and Linux
 - Alex Sayers (@asayers) - added support for netrc
