FaceFusion Docker
=================

> Next generation face swapper and enhancer.

[![Build Status](https://img.shields.io/github/actions/workflow/status/facefusion/facefusion-docker/ci.yml.svg?branch=master)](https://github.com/facefusion/facefusion-docker/actions?query=workflow:ci)
![License](https://img.shields.io/badge/license-MIT-green)


Installation
------------

Clone from GitHub:

```
git clone https://github.com/facefusion/facefusion-docker.git
```

Run the `CPU` container:

```
docker-compose -f docker-compuse.cpu.yml up
```

Run the `CUDA` container:

```
docker-compose -f docker-compuse.cuda.yml up
```


Usage
-----

Browse the `CPU` container:

```
http://localhost:7870
```

Browse the `CUDA` container:

```
http://localhost:7880
```


Documentation
-------------

Read the [documentation](https://docs.facefusion.io) for a deep dive.
