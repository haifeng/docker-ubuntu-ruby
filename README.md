# docker-ubuntu-ruby

The Ruby docker container based on Ubuntu.
Everything is customized for a Rails application.

# Steps to push to docker hub
- docker build -t ubuntu-ruby . -f Dockerfile
- docker tag ubuntu-ruby hfcao/ubuntu-ruby:[VERSION]
- docker push hfcao/ubuntu-ruby:[VERSION]