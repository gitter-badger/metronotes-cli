[![Latest Version](https://pypip.in/version/metronotes-cli/badge.svg)](https://pypi.python.org/pypi/metronotes-cli/)
[![Supported Python versions](https://pypip.in/py_versions/metronotes-cli/badge.svg)](https://pypi.python.org/pypi/metronotes-cli/)
[![License](https://pypip.in/license/metronotes-cli/badge.svg)](https://pypi.python.org/pypi/metronotes-cli/)
[![Gitter chat](https://badges.gitter.im/gitterHQ/gitter.png)](https://gitter.im/Metronotes/General)


# Description

[![Join the chat at https://gitter.im/Metronotes/metronotes-cli](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Metronotes/metronotes-cli?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

`metronotes-cli` is a command line interface for [`metronotes-lib`](https://github.com/Metronotes/metronotesd).


# Requirements

* [Patched Bitcoin Core](https://github.com/btcdrak/bitcoin/releases) with the following options set:

	```
	rpcuser=bitcoinrpc
	rpcpassword=<password>
	txindex=1
	server=1
	addrindex=1
	rpcthreads=1000
	rpctimeout=300
	```

# Installation

```
$ git clone https://github.com/Metronotes/metronotes-cli.git
$ cd metronotes-cli
$ python3 setup.py install
```


# Usage

* `$ metronotes-server --help`

* `$ metronotes-client --help`


# Further Reading

* [Official Project Documentation](http://metronotes.io/docs/)
