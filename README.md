# rem - repositories manager

    Ondrej Sika <ondrej@ondrejsika.com>
    https://github.com/ondrejsika/rem

Simple Git **re**positories **m**anager written for Python 2.


## Install

```
sudo pip install git+https://github.com/ondrejsika/rem.git
```

or

```
git clone git@github.com:ondrejsika/rem.git
cd rem
sudo pip install -e .
```

## Usage

Run `rem --help` for this help:

```
usage: rem [-h] [--dry] [--quiet] [-c CONFIG_FILE] {update} ...

positional arguments:
  {update}
    update              update repositories to state defined in config

optional arguments:
  -h, --help            show this help message and exit
  --dry                 prints out the commands without execution
  --quiet               quiet output doesn't shows command and outputs
  -c CONFIG_FILE, --config_file CONFIG_FILE
                        config file path, default is "rem.json"
```

## rem.json - configuration

see [example configuration](example/)


