docker-nethack-server
======================

Dockerfile for Public NetHack server

## Howto

    docker run --detach --name=nh --publish=23:23 matsuu/nethack-server

## Build

    docker build -t nethack-server .

## References

- [matsuu/docker-nethack](https://github.com/matsuu/docker-nethack)
- [NetHack 3.4.3: Home Page](http://www.nethack.org/)
- [alt.org - NetHack version used on NAO](http://alt.org/nethack/naonh.php)
- [Compiling - NetHackWiki, the NetHackWiki](http://nethackwiki.com/wiki/Compiling)
- [paxed/dgamelaunch](https://github.com/paxed/dgamelaunch)
- [HowTo setup dgamelaunch](http://nethackwiki.com/wiki/User:Paxed/HowTo_setup_dgamelaunch)
