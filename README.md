## what is it ?

media-downloader is a webapplication to simplify downloads from various filehosting sites.
It is basically a http frontend to run youtube-dl remotely.

Since [youtube-dl](https://rg3.github.io/youtube-dl) is used to perform the actual downloading, a large number of downloadsites is supported. you can find a list of supported filehosters [on the youtube-dl site](https://rg3.github.io/youtube-dl/supportedsites.html)

## how do i use it?

### installing and running with docker
//TODO
### accessing the ui via browser
//TODO
#### exposed ports

* 8080/tcp - access to web api and web ui

#### exposed volumes

* `/download` location for downloaded files
