# moc-lyrics
moc-lyrics is a simple bash script that fetches the lyrics of current song playing in MOC (music on console) music player.


### Dependencies :
- Perl - Perl (Practical Extraction and Reporting Language) originally developed by Larry Wall is a family of high-level, general-purpose, interpreted, dynamic programming languages. [Perl] is available in repositories of almost every Linux distribution under the sun. Use your distribution's package manager to install it.
- curl - [curl] is a command line tool and library for transferring data with URL syntax. curl is available in repositories of almost every Linux distribution so you can install curl easily via your package manager.


### Installation :
Very easy. Download [moc-lyrics-master.zip], extract it, and simply copy 'moc-lyrics' file to '/usr/local/bin/' directory,
 ```sh
$ sudo cp moc-lyrics /usr/local/bin/
```
Next make it executable,
```sh
$ sudo chmod a+x /usr/local/bin/moc-lyrics
```


### Usage :
Run moc-lyrics and it will fetch and print lyrics of the song currently playing in [MOC] music player.


### Credits :
[Federico Builes] - moc-lyrics wouldn't have been possible without wonderful [makeitpersonal] created by Federico.


### License :
[![Public Domain Mark](http://i.creativecommons.org/p/mark/1.0/88x31.png)](http://creativecommons.org/publicdomain/mark/1.0/)  
This work (<span property="dct:title">moc-lyrics</span>, by [<span property="dct:title">hakerdefo</span>](https://github.com/hakerdefo/moc-lyrics)), identified by [<span property="dct:title">hakerdefo</span>](https://hakerdefo.blogspot.com), is free of known copyright restrictions.

[perl]:https://www.perl.org
[curl]:http://curl.haxx.se
[moc-lyrics-master.zip]:https://github.com/hakerdefo/moc-lyrics/archive/master.zip
[MOC]:http://moc.daper.net
[Federico Builes]:https://github.com/febuiles
[makeitpersonal]:https://github.com/febuiles/makeitpersonal
