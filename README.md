win-youtube-dl
==============

A small GUI wrapper of youtube-dl (http://rg3.github.io/youtube-dl/download.html) Python script.
This application only works on 64-bit Windows (I'm lazy to make it work on 32-bit Windows).
Technically speaking, this application can work on Linux and Mac OSX, but I don't see a point of
having this application run those two OSes since Linux or Mac OSX users should be familar
with using a terminal.

How to build
------------
win-youtube-dl uses Gradle build system (http://www.gradle.org/) and launch4j (http://launch4j.sourceforge.net/)
It also requires Java 7.

    gradle -Plaunch4j=<launch4j_directory>

How to install
--------------
    Unzip win-youtube-dl.zip at (https://raw.github.com/fredyw/win-youtube-dl/master/win-youtube-dl.zip)
    Double click on win-youtube-dl.exe

Screenshot
----------
![win-youtube-dl screenshot](https://raw.github.com/fredyw/win-youtube-dl/master/win-youtube-dl.png)    
