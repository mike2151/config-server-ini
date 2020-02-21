# Config Server.ini

## About
Config Server.ini is a CLI used to set the default configuration for the `server.ini` file for web development with Hack Lang. [Web development with Hack Lang](https://docs.hhvm.com/hhvm/basic-usage/server) uses a file called server.ini for the default settings when you run a web server. Each web development project has different default settings for the server. Therefore, each project will require the developer to manually go to the `server.ini` file and edit the contents. This project
offers a script, `config-server-ini`, which looks in the calling directory for a `config.ini` file which has the contents that should go in the `server.ini` file. Then, the contents from `config.ini` are placed in `server.ini`, so the next time a server is run, the default settings are ready to go. 

## Installation

## Usage


