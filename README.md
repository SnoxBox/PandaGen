# PandaGen
> A dynamic, simple, relatively-fast shell generator

[![Python 3.7.3][python-image]][https://www.python.org/downloads/]

A simple shell generator with shells based on [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md) and [Pentestmonkey](http://pentestmonkey.net/cheat-sheet/shells/reverse-shell-cheat-sheet)reverse shell cheat sheets.


## Available Shell Types
- Bash
- Perl
- Ruby
- Golang
- Netcat
- Ncat
- Powershell
- Awk
- Lua
- Java
- Socat
- Nodejs
- Telnet
- Python

## Installation

OS X & Linux:

```sh
sudo apt install python3 python3-pip
git clone https://github.com/SnoxBox/PandaGen/
cd PandaGen
python3 pandagen.py
```

## Usage example

```
usage: pandagen.py [-h] [-ip IPADDR] [-p PORTNUM] [-t TYPE] [-l] [-a]

optional arguments:
  -h, --help            show this help message and exit
  -ip IPADDR, --ip IPADDR
                        IP address
  -p PORTNUM, --port PORTNUM
                        port number
  -t TYPE, --type TYPE  type of shell to generate
  -l, --list            list all available shell types
  -a, --all             generate all the shells
```

## Release History

* 0.0.1
    * First proper release

## To do

* Add more shells... duh.

## Meta

[https://github.com/SnoxBox]

## Contributing

1. Fork it (<https://github.com/SnoxBox/PandaGen/fork>)
2. Create your feature branch (`git checkout -b feature/PandaGen`)
3. Commit your changes (`git commit -am 'Add some PandaGen'`)
4. Push to the branch (`git push origin feature/PandaGen`)
5. Create a new Pull Request

