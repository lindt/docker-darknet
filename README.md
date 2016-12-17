[![Docker pulls](https://img.shields.io/docker/pulls/think/darknet.svg)](https://hub.docker.com/r/think/darknet/)
[![Docker Build](https://img.shields.io/docker/automated/think/darknet.svg)](https://hub.docker.com/r/think/darknet/)
[![Latest Tag](https://img.shields.io/github/tag/lindt/docker_darknet.svg)](https://hub.docker.com/r/think/darknet/)

# docker-darknet

Docker Image for Darknet ImageNet implementation

## Usage

`cat your_image.jpg | docker run -i think/darknet`

will provide the predictions for all categories found in the image.

## Example

### Image

<img src="https://cdn.rawgit.com/lindt/docker-darknet/master/eagle.jpg">

### Result

```
bald eagle: 0.809800
kite: 0.179002
vulture: 0.004752
prairie chicken: 0.000786
hen: 0.000612
```

## References

 - based on [darknet](https://github.com/pjreddie/darknet.git)
 - [weights](http://pjreddie.com/media/files/extraction.weights)
