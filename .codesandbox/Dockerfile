# CodeSandbox supports debian & ubuntu based images
FROM ubuntu
FROM node:lts
FROM php:8.1-cli-bullseye
RUN docker-php-source extract \
	# do important things \
	&& docker-php-source delete


# Example; install htop by default
RUN apt update -y && apt install -y htop

# The project will be mounted in /workspace by default

# Every new shell will open inside the built container

# On top of this build, we install `zsh`, `git` and `docker` as additional
# Docker layers.
