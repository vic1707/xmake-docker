# Docker Xmake

This repo contains a Dockerfile for building [xmake](https://github.com/xmake-io/xmake) images.

This repo is unofficial and not affiliated with xmake.

Multiple tags are available:
  - `vX.X.X`: GCC vX.X.X (one of the stable releases)
  - `dev.<HASH>`: GCC dev (latest version from `dev` branch)
  - `alpine-vX.X.X` Alpine vX.X.X (one of the stable releases)

## Usage

### Run

```bash
docker run --rm -v $PWD:/app vic1707/xmake:<tag-name> xmake --version
```
