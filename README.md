## Your star is my power :rocket: :star: :star: :star: :star: :star:
![](https://github.com/fanux/tetris/blob/master/img/tetris.png?raw=true)
## Build
```
$ cd src && make
$ ./game
$ g++ --version
g++ (GCC) 4.8.5 20150623 (Red Hat 4.8.5-4)
$ uname -a
Linux docker-86-106 3.10.0-327.22.2.el7.x86_64 #1 SMP Thu Jun 23 17:05:11 UTC 2016 x86_64 x86_64 x86_64 GNU/Linux
```

## Ship on docker

Build and launch

```
$ docker build -t tetris:latest .
$ docker run -it tetris:latest
```

Just launch
```
$ docker run -it fanux/tetris:latest
```

Play well in iTerm
