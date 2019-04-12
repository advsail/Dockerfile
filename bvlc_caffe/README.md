# Dockerfile Description

## CPU Version

The CPU version docker file was forked from [BVLC/caffe](https://github.com/BVLC/caffe) docker file with minor modifications. The default `pip` version in Ubuntu 16.04 is `8.1.1`. In the original dockerfile, running `pip install --upgrade pip` will upgrate `pip` to version >18.0, and `python-pip-8.1.1` installed is conflicting with `pip > 18.0`, so the `pip` version is binded to `8.1.1` to avoid this error.


## GPU Version

