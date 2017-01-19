#ytdl_ffmpeg

####Build

`docker build -t arcaster/ytdl_ffmpeg .`

####Run

```
docker run -v `pwd`:/tmp/workdir ytdl_test https://www.youtube.com/watch?v=AfAKtLVMd0k [any other youtube-dl opts]
```