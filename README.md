Image Stream and Template Examples
==================================
Various examples of image streams and templates for OpenShift 3.

## Memcached
[Memcached](https://raw.githubusercontent.com/luciddreamz/examples/master/memcached/image-streams/memcached-debian.json) - Provides an image stream for Memcached, a distributed memory caching system. For more information see the [source repository](https://hub.docker.com/_/memcached/).

Add the Memcached image stream to your namespace:

```
$ oc create -f https://raw.githubusercontent.com/luciddreamz/examples/master/memcached/image-streams/memcached-debian.json
```