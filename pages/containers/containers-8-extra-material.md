Containers can be large and complicated, but once you start using them regularly
you'll find that you start understand these complexities. There are lots of
different things you can do with images and containers in general, especially
when it comes to optimising build time or final image size. Here is some small
tips and tricks that you can be inspired from!

If you want to read more about containers in general you can check out these
resources:

* A "Get started with Docker" at [docker.com](https://docs.docker.com/get-started/).
* An [early paper](https://arxiv.org/abs/1410.0846) on the subject of using
  Docker for reproducible research.

## More on volumes

In the tutorial we mounted directories inside containers using the `-v 
SOURCE:TARGET` syntax with `docker run`. We mentioned that volumes was a 
more advanced way of handling data generated by containers...

## Building for different platforms