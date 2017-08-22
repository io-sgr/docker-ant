## Simple Apache Ant docker images on top of Ubuntu

This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/sgrio/ant/) published to the public [Docker Hub](https://hub.docker.com/).

### Docker Tags

`sgrio/ant` provides one single tagged image:

* Default (Your best choice)
  * `latest`: Apache Ant version `1.10.1`

### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/sgrio/ant/) from public [Docker Hub](https://hub.docker.com/): `docker pull sgrio/ant`

### Usage

    docker run -it --rm sgrio/ant ant version
