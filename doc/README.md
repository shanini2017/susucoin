Susucoin Core
=============

Setup
---------------------
Susucoin Core is the original Susucoin client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Susucoin transactions (which is currently more than 100 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Susucoin Core, visit [susukino.com](https://susukino.com/).

Running
---------------------
The following are some helpful notes on how to run Susucoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/susucoin-qt` (GUI) or
- `bin/susucoind` (headless)

### Windows

Unpack the files into a directory, and then run susucoin-qt.exe.

### macOS

Drag Susucoin-Core to your applications folder, and then run Susucoin-Core.

### Need Help?

* See the documentation at the [Susucoin Wiki](https://en.susucoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#susucoin](http://webchat.freenode.net?channels=susucoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=susucoin).
* Ask for help on the [SusucoinTalk](https://susucointalk.org/) forums, in the [Technical Support board](https://susucointalk.org/index.php?board=4.0).

Building
---------------------
The following are developer notes on how to build Susucoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Susucoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/susucoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [SusucoinTalk](https://susucointalk.org/) forums, in the [Development & Technical Discussion board](https://susucointalk.org/index.php?board=6.0).
* Discuss project-specific development on #susucoin-core-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=susucoin-core-dev).
* Discuss general Susucoin development on #susucoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=susucoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
