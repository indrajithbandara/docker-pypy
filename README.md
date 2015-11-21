A Docker image for PyPy 4.0.1
=============================

[![](https://badge.imagelayers.io/jeethu/pypy:latest.svg)](https://imagelayers.io/?images=jeethu/pypy:latest 'Get your own badge on imagelayers.io')

A minimal Ubuntu 14.04.03/Debian (Jessie) based docker image for PyPy 4.0.1. There are also `onbuild` variants for both.

- [pypy:4.0.1](https://github.com/jeethu/docker-pypy/blob/master/ubuntu/Dockerfile) __compatible with python-2.7.10__
- [pypy:4.0.0](https://github.com/jeethu/docker-pypy/blob/4.0.0/ubuntu/Dockerfile) __compatible with python-2.7.10__
- [pypy:4.0.0-onbuild](https://github.com/jeethu/docker-pypy/blob/master/ubuntu/onbuild/Dockerfile) __compatible with python-2.7.10__
- [pypy:4.0.0-debian](https://github.com/jeethu/docker-pypy/blob/master/debian/Dockerfile) __compatible with python-2.7.10__
- [pypy:4.0.0-debian-onbuild](https://github.com/jeethu/docker-pypy/blob/master/debian/onbuild/Dockerfile) __compatible with python-2.7.10__

Setup:
---

To build an Ubuntu 14.04 based image:
```
make ubuntu
```

To build a Debian(Jessie) based image:

```
make debian

```

To build everything:

```
make
```

To run the PyPy shell:

```
docker run -it --rm jeethu/pypy:4.0.1
```

Older PyPy builds are on the following branches

* [4.0.0](https://github.com/jeethu/docker-pypy/tree/4.0.0)
* [2.6.0](https://github.com/jeethu/docker-pypy/tree/2.6.0)
* [2.5.1](https://github.com/jeethu/docker-pypy/tree/2.5.1)
* [2.5.0](https://github.com/jeethu/docker-pypy/tree/2.5.0)
* [2.4.0](https://github.com/jeethu/docker-pypy/tree/2.4.0)

Trusted builds are available on the [Docker Hub Registry](https://registry.hub.docker.com/u/jeethu/pypy/).

Credits:
---

* [Najam Khan](https://github.com/najamkhn)
	* Contributed a Debian based build.
