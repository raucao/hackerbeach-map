# Hacker Beach Map (Phu Quoc)

This is an interactive map app, showing points of interest to participants of
Hacker Beach 12/13 on Phu Quoc Island, Vietnam. You can launch it from:

[http://map.hackerbeach.org](http://map.hackerbeach.org)

It works well on both desktop browsers and smartphones, so you can take it with
you when exploring the island.

## Contributions welcome!

You can contribute new places by forking the repo, editing `places.json` and
then doing a pull request. The format is a subset of
[GeoJSON](http://geojson.org/), but it's really just a few attributes.

The icons are sourced from http://mapicons.nicolasmollet.com and all 700+ icons
are included. For the `icon` property, just browse their directory and use the
lowercase name you see on the detail page of an icon.

You can also contribute improvements to the app itself if you like (it's really
simple), or use the code for your own purposes.

## Install

You can also install the app in various formats from 5apps or add it to your
home screen to install on iOS:

https://5apps.com/apps/50e4132fbc73cb4548000133

## Tip Jar

If you find this helpful and want to buy me a beer, you can flattr the app on
5apps (same link as above), or send some Bitcoin to the following wallet:

1JYdQzPuk1hXLekWTk8Hwgj4pM8LHaKPNf

## To Do

We had some ideas for new features already. Hack away, if you like:

* Add the possibility of sharing your being at a place from the popup (create a
  URL that opens the app with that place selected)
* Create some helper that makes it easy to contribute a new place from the
  current location
* Add some kind of URI array to the properties and render buttons that link to
  e.g. Wikipedia, Foursquare, etc.
* Add a tile layer switching control. See https://gist.github.com/1804938 for
  example configs

## License

Copyright (c) 2012 Sebastian Kippe <sebastian@kip.pe>

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
