# song-dl
download the best matching song from youtube


## usage

### command line

```
$ npm intall -g song-dl
$ sdl "song name and artist" -o outputfile.mp3 -k <YOUTUBE API KEY>
```

### node

```
var sdl = require('song-dl');

sdl('songname and artist', 'output filename', 'youtube apikey', function(err) {
    if(!err) {
      console.log('download success');
    }
});
```
