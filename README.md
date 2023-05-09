# containers

![CI Build Status](https://github.com/torbendury/containers/actions/workflows/docker-image.yml/badge.svg)

A tiny, tidy repository for keeping my image manifests. Mainly used for development and base-image builds.

## Available Images

```bash
# PYTHON development container
docker run -ti --rm --name python torbendury/python-dev:latest
# PYTHON analysis container
docker run -ti --rm --name python torbendury/python-analysis:latest
# GOLANG development container
docker run -ti --rm --name golang torbendury/golang-dev:latest
```

### development

- Python 3.11
  - including an image for data analysis that comes with several tools pre-installed
- Golang 1.20.4

### base-images

TO BE DONE!

- Python
- Golang
