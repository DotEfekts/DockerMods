# ssh - Docker mod for any container

This mod adds ssh to any container, to be installed/updated during container start.

In any container docker arguments, set an environment variable `DOCKER_MODS=dotefekts/mods:universal-ssh`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=dotefekts/mods:universal-ssh|linuxserver/mods:universal-mod2`
