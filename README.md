![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# Darknet
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

## Table of Contents
+ Installation
    - macOS
        + CPU Only
        + CPU + GPU


## Installation
In this section we will cover the downloading and installing of `darknet`.

### macOS
`darknet` can be installed for `macOS`. First you must decide on which install you would like: `CPU-only or CPU + GPU`. We will first look at CPU-only

#### CPU-Only Install
To install the `CPU-Only` version of `darknet`, clone the git repository, switch to the `macOS` branch, and execute the `make` command as follows:
```
$ git clone https://github.com/RagingTiger/darknet.git
$ git checkout macos
$ make
```
After many lines of compiler output, you should have an executable file named `darknet` sitting in your repository. Visit https://pjreddie.com/darknet/yolo/ and try out some of the examples!

#### CPU + GPU Install
To install `darknet` with GPU support, you will first need to install CUDA. [*Visit this site for more details and guidance on installing CUDA for macOS*](https://github.com/RagingTiger/CUDAInstall). After successfully installing CUDA, you will simply need to clone the git repository, switch to the `macos-gpu` branch, and execute `make` as follows:
```
$ git clone https://github.com/RagingTiger/darknet.git
$ git checkout macos-gpu
$ make
```
Like the `CPU-Only` install, you should now have a `darknet` executable sitting in your repository. Visit https://pjreddie.com/darknet/yolo/ and try out some of the examples!
