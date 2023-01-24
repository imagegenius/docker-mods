# Redis - Universal docker mod

This mod adds redis, to be installed/updated during container start.

The `redis.conf` file is located at `/config/redis/` - modify this file to what you need.

In docker arguments, set an environment variable `DOCKER_MODS=imagegenius/mods:universal-redis`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:swag-ffmpeg|linuxserver/mods:swag-mod2`
