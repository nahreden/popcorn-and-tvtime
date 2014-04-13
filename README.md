#Popcorn-time and TV-time Combined

### Idea

To allow any computer user to watch Movies and TV shows easily streaming from torrents, without any particular knowledge.


### Status

Under development (RC) for Mac OSX - Windows - Linux.

### APIs

**Currently used:**
- [YIFY](http://yts.re/api) movie torrents API.
- [EZTV via Apify](https://apify.heroku.com/resources/4fe34d909e610f0001000006) tv torrents API.
- [YifySubtitles](http://www.yifysubtitles.com) for subtitles
- [Trakt.tv](https://trakt.tv/) for tv metadata.

### Development

See [Development's page](https://github.com/popcorn-official/popcorn-app/wiki/Development)


## Any problem?

### Error about missing libudev.so.0
Search for libudev.so.0 on your distribution. Most of the time it can be easily fixed by creating a symbolic link from libudev.so to libudev.so.0

See: https://github.com/rogerwang/node-webkit/wiki/The-solution-of-lacking-libudev.so.0

### Error "Gtk-WARNING **: cannot open display:"
Try running `export DISPLAY=:0.0`

### Error "The video format is not supported"
See: https://github.com/rogerwang/node-webkit/wiki/Support-mp3-and-h264-in-video-and-audio-tag
