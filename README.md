# Setting up Caffe & ImageNet

Install and setup notes for [Caffe](http://caffe.berkeleyvision.org) and ImageNet. Caffe is a deep learning framework.

## General Setup
- http://caffe.berkeleyvision.org/installation.html

## Setup Notes
### Amazon Pre-built AMIs
- Amazon Cuda Ubuntu AMI https://github.com/BVLC/caffe/wiki/Caffe-on-EC2-Ubuntu-14.04-Cuda-7
	- AMI https://console.aws.amazon.com/ec2/v2/home?region=us-east-1#LaunchInstanceWizard:ami=ami-763a311e
- Bitfusion AWS EC2 GPU enabled Caffe AMI https://github.com/BVLC/caffe/wiki/AWS-EC2-GPU-enabled-Caffe-AMI
### Install
- Ubuntu Installation http://caffe.berkeleyvision.org/install_apt.html
- Source git clone https://github.com/BVLC/caffe
- http://installing-caffe-the-right-way.wikidot.com/start

## Workarounds
- http://caffe.berkeleyvision.org/installation.html#compilation
        - Error 1: ./include/caffe/common.hpp:5:27: fatal error: gflags/gflags.h: No such file or directory compilation terminated. https://github.com/BVLC/caffe/wiki/Ubuntu-14.04-ec2-instance
- Could not insert 'nvidia_352': No such device http://stackoverflow.com/questions/32493904/could-not-insert-nvidia-352-no-such-device
- ctypes error: libdc1394 error: Failed to initialize libdc1394 http://stackoverflow.com/questions/12689304/ctypes-error-libdc1394-error-failed-to-initialize-libdc1394

## ImageNet
- Brewing ImageNet http://caffe.berkeleyvision.org/gathered/examples/imagenet.html


