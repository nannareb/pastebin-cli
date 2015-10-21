# pastebin-cli
A command line program for the pastebin API

# INSTALLATION

1. drop pastebin script into your bin directory
2. run the script once.
3. go to ~/.config/pastebin/pastebin.conf and drop your developer api key in.  found at http://pastebin.com/api#1


# help

usage: pastebin [-h] [-p] [--unlisted] [-v] [-n NAME] [-u] [-g GET]
                [-d DELETE] [--get-user-key] [--username USERNAME]
                [--password PASSWORD]

A command line interface for pastebin

optional arguments:
  -h, --help            show this help message and exit
  -p, --private         set paste to be private
  --unlisted            set paste to be unlisted
  -v, --verbose         enable verbose output
  -n NAME, --name NAME  the title of the paste
  -u, --upload          upload content from stdin
  -g GET, --get GET     get paste by id
  -d DELETE, --delete DELETE
                        delete a paste
  --get-user-key        get the users login key
  --username USERNAME   sets username for use with get-user-key
  --password PASSWORD   sets password for use with get-user-key
