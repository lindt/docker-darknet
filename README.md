[![Docker pulls](https://img.shields.io/docker/pulls/think/darknet.svg)](https://hub.docker.com/r/think/darknet/)
[![Docker Build](https://img.shields.io/docker/automated/think/darknet.svg)](https://hub.docker.com/r/think/darknet/)

# docket-darknet

Docker Image for Darknet ImageNet implementation

## Usage

`cat your_image.jpg | docker run -i think/darknet`

will provide the predictions for all categories found in the image.

## References

 - based on [darknet](https://github.com/pjreddie/darknet.git)
 - [weights](http://pjreddie.com/media/files/extraction.weights)
