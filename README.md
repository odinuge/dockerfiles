# dockerfiles
> Just a bunch of useful utilites packed into dockerfiles

### Yapf

Simple container that is useful for formatting python code with yapf
on the fly.

Usage
```bash
$ docker run --rm -it -v $PWD:/code/ odinuge/yapf
$ docker run --rm -it -v $PWD:/code/ odinuge/yapf yapf -ir source_code/
```
