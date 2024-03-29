# dghubble/python3

[dghubble/python3](https://registry.hub.docker.com/u/dghubble/python3/) is a Docker image providing Python 3.4, [pip](https://packages.debian.org/wheezy/python3-pip), [distribute](https://pypi.python.org/pypi/distribute/0.7.3), and [python3-dev](https://packages.debian.org/wheezy/python3-dev) on [Debian](https://www.debian.org/releases/) Jessie 8.0 (stable).

## Features

From from Debian [stable](https://packages.debian.org/stable/):

  * Python 3.4.2
  * python3-dev

From [PyPI](https://pypi.python.org/pypi):

  * pip3 1.5.6
  * distribute 0.7.3

## Build

    cd dghubble-docker/python3
    docker build -t dghubble/python3:v1 .

## Start

    docker run -t -i dghubble/python3

## License

[MIT License](LICENSE)

