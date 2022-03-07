<h1 align="center">Mov-Cli</h1>
<p align="center"><strong>Notflix Fork</strong></p>
<p align="center">f@#k netflix use mov-cli a tool which search magnet links and stream it with peerflix</p>

##
<p align="center">
<img src="./preview.gif" alt="Video Preview" width="500px">
</p>

> Watch this video to understand - [bugswriter's notflix](https://youtu.be/FbE19_omaWY)

### How does this work?

This is a shell script. It scape 1337x and get the magnet link.
After this it use [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Installation

### cURL
cURL **mov-cli** to your **$PATH** and give execute permissions.

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/ludovici-philippus/mov-cli/master/mov-cli" -o /usr/local/bin/notflix
$ sudo chmod +x /usr/local/bin/mov-cli
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `notflix` from your **$PATH**, for example `sudo rm -f /usr/local/bin/notflix.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

