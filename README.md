[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/clouddns.svg)](https://hub.docker.com/r/rubygem/clouddns/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/clouddns.svg)](https://hub.docker.com/r/rubygem/clouddns/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/clouddns.svg)](https://hub.docker.com/r/rubygem/clouddns/)
[![Gem Downloads](https://img.shields.io/gem/dt/clouddns.svg)](https://rubygems.org/gems/clouddns/)
# clouddns

Auto-Generated Docker image for clouddns to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/clouddns`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/clouddns`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/clouddns`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/clouddns/)
