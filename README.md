# Setting up Caffe & ImageNet

Install and setup notes to get first get [Caffe](http://caffe.berkeleyvision.org) and then ImageNet up and running. Caffe is a deep learning framework.

## General Setup
- http://caffe.berkeleyvision.org/installation.html

## Setup Notes
- Amazon Cuda Ubuntu AMI https://github.com/BVLC/caffe/wiki/Caffe-on-EC2-Ubuntu-14.04-Cuda-7
- Ubuntu Installation http://caffe.berkeleyvision.org/install_apt.html
- git clone https://github.com/BVLC/caffe
- http://caffe.berkeleyvision.org/installation.html#compilation
    - Error 1: ./include/caffe/common.hpp:5:27: fatal error: gflags/gflags.h: No such file or directory
compilation terminated. https://github.com/BVLC/caffe/wiki/Ubuntu-14.04-ec2-instance
- http://installing-caffe-the-right-way.wikidot.com/start

## Workarounds
- Could not insert 'nvidia_352': No such device http://stackoverflow.com/questions/32493904/could-not-insert-nvidia-352-no-such-device
- ctypes error: libdc1394 error: Failed to initialize libdc1394 http://stackoverflow.com/questions/12689304/ctypes-error-libdc1394-error-failed-to-initialize-libdc1394

## ImageNet
- Brewing ImageNet http://caffe.berkeleyvision.org/gathered/examples/imagenet.html


