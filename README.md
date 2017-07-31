&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Getting Started With Docker](https://github.com/ajaymache/getting-started-with-docker/blob/master/misc/images/DockerLogo.png)

## Introduction
This repository aims at getting you started with [docker](https://www.docker.com/) by setting up environment for machine learning/deep learning libraries and frameworks.

### What is docker?
- Docker is the world’s leading software container platform. Developers use Docker to eliminate “works on my machine” problems when collaborating on code with co-workers.

- Operators use Docker to run and manage apps side-by-side in isolated containers to get better compute density. 

- Enterprises use Docker to build agile software delivery pipelines to ship new features faster, more securely and with confidence for both Linux and Windows Server apps.

### What is an image?
- An image is a lightweight, stand-alone, executable package that includes everything needed to run a piece of software, including the code, a runtime, libraries, environment variables, and config files.

### What is a container?
- A container is a runtime instance of an image — what the image becomes in memory when actually executed. It runs completely isolated from the host environment by default, only accessing host files and ports if configured to do so.

- Using containers, everything required to make a piece of software run is packaged into isolated containers. Unlike VMs, containers do not bundle a full operating system - only libraries and settings required to make the software work are needed.

- This makes for efficient, lightweight, self-contained systems and guarantees that software will always run the same, regardless of where it’s deployed. To learn more about containers click [here](https://www.docker.com/what-container).

## Installing docker
Install the docker application following the installation guide for your platform from [here](https://docs.docker.com/engine/installation/)

## Setting up the environment
- The Docker Engine client runs natively on **Linux**, **macOS**, and **Windows**. By default, these clients connect to a local Docker daemon running in a virtual environment managed by Docker, which provides the required features to run Linux-based containers within OS X or Windows, or Windows-based containers on Windows.

- The steps mentioned below are performed with the docker application installed on **OSX (macOS)**. Following the steps mentioned below, you should be able to setup a customized docker image and push to [dockerhub](https://hub.docker.com/).

### Starting with a base image
- While making a custom docker image most of the times you will encounter that one usually starts with a base image. Here we will be using **ubuntu** as our base image.

- Please note that we **do not** have to make the ubuntu image from scratch since its already been officially made by the community and we can use the same image as the starting point or base for creating our own image.

- To get **ubuntu** as the base image from the public repository on dockerhub do the following steps:
  1. Open terminal
  2. To check if docker daemon is running type the following command in the terminal:
  ```docker
     docker version
     ```

Update README.md

