# Deep Learning Reference Stack
[![](https://images.microbadger.com/badges/image/clearlinux/stacks-dlrs-oss.svg)](http://microbadger.com/images/clearlinux/stacks-dlrs-oss "Get your own image badge on microbadger.com")

This variant is built with Eigen

# Building Locally

```
docker build --no-cache -t clearlinux/stacks-dlrs-oss .     # Optimized for Intel Architecture
```

## Optional Build ARGs

* `swupd_args` specifies
  [swupd update](https://clearlinux.org/documentation/clear-linux/guides/maintenance/swupd-guide#perform-a-manual-update)
  flags passed to the update during build.

# Pulling from Dockerhub
---------------------------

```
docker pull clearlinux/stacks-dlrs-oss
```

Default build args in Docker are on: https://docs.docker.com/engine/reference/builder/#/arg