ffmpeg-proxy
========================


Simple proxy server for tests usage. It has been designed for proxying HLS (or other) streams to MPEG-TS.


## Usage

Example URLs to launch with your favorite hardware or software media player: 

`http://127.0.0.1:32033/http://streaming.service.com/live.m3u8`
`http://127.0.0.1:32033/https://streaming.service.com/live.m3u8`
`http://127.0.0.1:32033/http://streaming.service.com/live%2Em3u8`
`http://your_local_ip_address:32033/http://streaming.service.com/live.m3u8`


## OSX Install

* Install homebrew packet manager by running `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` 
* Run `brew install ffmpeg` 
* Install ffmpeg-proxy with `/bin/zsh <(curl -fsSL https://raw.githubusercontent.com/aisayev/ffmpeg-proxy/master/contrib/ffmpeg-proxy-osx-install)`
* To uninstall use `/bin/zsh <(curl -fsSL https://raw.githubusercontent.com/aisayev/ffmpeg-proxy/master/contrib/ffmpeg-proxy-osx-uninstall)`

