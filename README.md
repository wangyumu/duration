# duration

Parse standard units of time, based on go's stdlib time implementation.

[Drone]: http://ci.maze.io/go/duration
[Drone Widget]: http://ci.maze.io/api/badges/go/duration/status.svg
[GoDoc]: https://godoc.org/maze.io/duration.v1
[GoDoc Widget]: https://godoc.org/maze.io/duration.v1?status.svg
[Codebeat]: https://codebeat.co/projects/git-maze-io-go-duration
[Codebeat Widget]: https://codebeat.co/badges/61daef24-a133-4838-aafc-c427e02a7a8e


# how to use

In case:
```
go: github.com/minio/mc@v0.0.0-20210716165100-bfafb966324c requires
        maze.io/x/duration@v0.0.0-20160924141736-faac084b6075: unrecognized import path "maze.io/x/duration": https fetch: 
Get "https://maze.io/x/duration?go-get=1": dial tcp 94.23.210.189:443: connectex: A connection attempt failed because the connected party did not properly respond after a period of time, or established connection failed because connected host has failed to respond.
```

add this line to go.mod
`replace maze.io/x/duration v0.0.0-20160924141736-faac084b6075 => github.com/wangyumu/duration v0.0.0-20220823032928-7de17be84cab`

