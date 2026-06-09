# NT72690\_FUR7.2\_OpenSourceSoftware

## Environment
Individual build components may list different versions of Ubuntu for compilation in their respective readme / build instruction files.
However, all modules here in were compiled successfully in Ubuntu 22.04 (jammy).

### Preparing your Ubuntu environment
Run the following commands:
```
sudo apt-get update
sudo apt-get install docker.io docker-buildx make
```

You may also want to add your user to the docker group (`adduser <username> docker`), and log out
and back in. This will remove the need to run docker commands via sudo.

## Build Instructions 
After downloading the tarball, run the following commands:
```
tar xzf NT72690_FUR7.2.tar.gz
cd NT72690_FUR7.2
./build.sh all
```

Further instructions for the contents of the tarball can be found in its included README.

Download the tarball here: 
https://d2mi77xcznxniv.cloudfront.net/index.html?file=NT72690_FUR7.2.tar.gz

