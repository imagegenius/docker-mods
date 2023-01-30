# Nextcloud - Swag Docker Mod

This mod installs nextcloud dependencies so you can run nextcloud on swag.

you may need to add `-e LD_PRELOAD="/usr/lib/preloadable_libiconv.so"` if there are relevant errors.

In docker arguments, set an environment variable `DOCKER_MODS=imagegenius/mods:swag-nextcloud`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:swag-ffmpeg|linuxserver/mods:swag-mod2`
