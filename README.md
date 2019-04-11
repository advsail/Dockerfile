# Description of Dockerfiles

The changes and improvements made on existing docker images are described here.

## improve bclc caffe

Base docker image: `bvlc/caffe:cpu`

Build command: `docker build  -t caffe_cpu:tag .`

Changes made

| Tag | Changes (based on previous tag) |
| --- | --- |
| `bvlc/caffe:cpu` | Base image |
| `caffe_cpu:v1.0` | (1) Update system <br> (2) Install vim|
