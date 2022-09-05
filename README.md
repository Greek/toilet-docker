# toilet-docker

`toilet-docker` is a used to dictate the configuration and deployment of Toilet bot
and other Toilet services.

This repository automagically sets up the environment to provide resources without external
services. If you're using an external host for a database or Redis, you should simply use
a `docker` command to deploy the bot with a basic environment file.

## How to use?

To use this, follow these instructions:

1. Copy `.env.example` and change the variables. (Some can be deleted, read info in file.)
2. If you need, change any config in `redis/redis.conf`.

Now you can run `docker-compose up -d` and everything should run! Congrats! 