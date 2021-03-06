# telebot
C Library for Telegram bot API that uses json-c and libcurl

## Compilation
You need to install libraries and build tools such as CMake.
On Debian-based Linux distributions you can do it as follows:
```sh
sudo apt-get install libcurl3-dev libjson0 libjson0-dev cmake binutils make
```
On Mac OSX, first insall macports from [MacPorts](https://www.macports.org/install.php) and in Terminal
```sh
sudo port install cmake json-c curl
```
To compile the library execute following commands:
```sh
cd [your repository]
mkdir -p Build && cd Build
cmake ../
make
```
This will create `echobot` executable under `Build/test` folder. This is a simple dummy bot which echoes back the messages sent to it. Head over to [Telegram Bots](https://core.telegram.org/bots) page to read about how to register your brand new echo bot with Telegram platform and see it in action.
