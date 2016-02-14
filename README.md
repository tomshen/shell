# shell
Useful shell commands

## Convert FLAC to MP3

```sh
$ parallel ffmpeg -i {} -qscale:a 0 {.}.mp3 ::: *.flac
```
