# Xori in Docker

## Start

_Please note this will only work with docker locally due to hardcoded references to localhost at the moment._

Simply start with `docker-compose up -d`, then access Xori via http://localhost:3000.

## About

This Docker image is utilizing supervisord to keep both the API and GUI server running at the same time, restarting them if necessary.

A named volume called "xori-dynamic" is used to cache analyzed files.
