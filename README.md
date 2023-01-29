# PostgreSQL - Universal Docker Mod

**under development**

This mod installs and starts postgresql, to be installed/updated during container start.

In docker arguments, set an environment variable `DOCKER_MODS=imagegenius/mods:universal-postgres`

PostgreSQL version can be specified in the `PG_VERSION` variable, eg. `PG_VERSION=14`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:swag-ffmpeg|linuxserver/mods:swag-mod2`
