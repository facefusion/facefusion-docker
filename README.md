FaceFusion Docker
=================

> Industry leading face manipulation platform.

[![Build Status](https://img.shields.io/github/actions/workflow/status/facefusion/facefusion-docker/ci.yml.svg?branch=master)](https://github.com/facefusion/facefusion-docker/actions?query=workflow:ci)
[![Docker Hub](https://img.shields.io/docker/v/facefusion/facefusion/3.4.0-cpu?label=docker-hub)](https://hub.docker.com/r/facefusion/facefusion/tags?name=3.4.0-cpu)
[![Docker Hub](https://img.shields.io/docker/v/facefusion/facefusion/3.4.0-cuda?label=docker-hub)](https://hub.docker.com/r/facefusion/facefusion/tags?name=3.4.0-cuda)
[![Docker Hub](https://img.shields.io/docker/v/facefusion/facefusion/3.4.0-tensorrt?label=docker-hub)](https://hub.docker.com/r/facefusion/facefusion/tags?name=3.4.0-tensorrt)
[![Docker Hub](https://img.shields.io/docker/v/facefusion/facefusion/3.4.0-rocm?label=docker-hub)](https://hub.docker.com/r/facefusion/facefusion/tags?name=3.4.0-rocm)
![License](https://img.shields.io/badge/license-OpenRAIL--S-green)


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

Run the `TensorRT` container:

```
docker compose -f docker-compose.tensorrt.yml up
```

Run the `ROCm` container:

```
docker compose -f docker-compose.rocm.yml up
```


Usage
-----

Browse the `CPU` container:

```
http://localhost:7865
```

Browse the `CUDA` container:

```
http://localhost:7870
```

Browse the `TensorRT` container:

```
http://localhost:7875
```

Browse the `ROCm` container:

```
http://localhost:7880
```


Documentation
-------------

Read the [documentation](https://docs.facefusion.io) for a deep dive.
