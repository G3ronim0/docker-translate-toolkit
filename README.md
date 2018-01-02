docker-translate-toolkit
========================
Python [Translate Toolkit][tt] inside a docker container

# Usage example
```shell
$ docker run --rm -it -v $(pwd):/data colthreepv/docker-translate-toolkit xliff2po /data/file.xliff /data/file.po
```

[tt]: https://github.com/translate/translate
