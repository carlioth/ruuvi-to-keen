ruuvi-to-keen
=============
Node.JS app to relay RuuviTag measurements to Keen.io.

Requires [Noble](https://github.com/sandeepmistry/noble)

Requires a [Keen.io](https://keen.io) account.

## Install

```sh
npm install
```
## Start

```bash
KEEN_PROJECTID=aaaaaaaaaa KEEN_WRITEKEY=aabbccddeeff screen node index.js
```
Press CTRL+A CTRL+D to detach from screen and to leave the application running.

To get back to the screen:
```bash
screen -r
```
