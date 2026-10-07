# NT72690\_FUR7.2\_OpenSourceSoftware

## Identifiers
|Item|Value
|---|---
|Chipset|NT72690
|Release|FUR7.2
|FW Versions|90.720.X.Y
|Download Link|https://d2mi77xcznxniv.cloudfront.net/index.html?file=NT72690_FUR7.2.tar.gz

## Environment
Individual build components may list different versions of Ubuntu for compilation in their respective README or build instruction files.
However, all components were compiled successfully on Ubuntu 22.04 (jammy).

### Preparing your Ubuntu environment
Run the following commands:
```
sudo apt-get update
sudo apt-get install docker.io docker-buildx make
```

You may also want to add your user to the docker group (`adduser <username> docker`), and log out
and back in. This will remove the need to run docker commands via sudo.

### Memory Advisory
Be advised that compiling the SoC vendor kernel requires a large amount of RAM- more than 32GB.

## Build Instructions 
After downloading the tarball, run the following commands:
```
tar xzf NT72690_FUR7.2.tar.gz
cd NT72690_FUR7.2
./build.sh all
```

Further instructions for the contents of the tarball can be found in its included README.

Download the source archive here: 
https://d2mi77xcznxniv.cloudfront.net/index.html?file=NT72690_FUR7.2.tar.gz

