# Config Server.ini

## About

Config Server.ini is a CLI used to set the default configuration for the `server.ini` file for web development with Hack Lang. [Web development with Hack Lang](https://docs.hhvm.com/hhvm/basic-usage/server) uses a file called server.ini for the default settings when you run a web server. Each web development project has different default settings for the server. Therefore, each project will require the developer to manually go to the `server.ini` file and edit the contents. This project
offers a script, `config-server-ini`, which looks in the calling directory for a `config.ini` file which has the contents that should go in the `server.ini` file. Then, the contents from `config.ini` are placed in `server.ini`, so the next time a server is run, the default settings are ready to go. 

## Installation

### Download/Clone The Repo And Place In Bin

Download or clone the repo:
`git clone https://github.com/mike2151/config-server-ini.git`

Move the file to bin:
`cp config-server-ini/bin/config-server-ini /usr/local/bin`

Then, you can access the tool by typing: `config-server-ini` in a command line

## Usage

`config-server-ini` : looks in the current directory for a `config.ini` file and places the contents of the file in the `server.ini` file.
`config-server-ini path/to/file` : places the contents of the file in the `server.ini` file
`config-server-ini default` : restores the default `server.ini` file which comes when you first install HHVM and Hack

