FaceFusion Docker
=================

> Next generation face swapper and enhancer.

[![Build Status](https://img.shields.io/github/actions/workflow/status/facefusion/facefusion-docker/ci.yml.svg?branch=master)](https://github.com/facefusion/facefusion-docker/actions?query=workflow:ci)
![License](https://img.shields.io/badge/license-MIT-green)


Installation
------------

Clone the repository:

```
git clone https://github.com/facefusion/facefusion-docker.git
```

Run the `CPU` container:

```
docker compose -f docker-compose.cpu.yml up
```

Run the `CUDA` container:

```
docker compose -f docker-compose.cuda.yml up
```

Run the `ROCM` container:

```
docker compose -f docker-compose.rocm.yml up
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

Browse the `ROCM` container:

```
http://localhost:7890
```


Documentation
-------------

Read the [documentation](https://docs.facefusion.io) for a deep dive.
