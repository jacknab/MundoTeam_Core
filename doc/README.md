Mundoteam Core
=============

Setup
---------------------
Mundoteam Core is the original Mundoteam client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Mundoteam transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Mundoteam Core, visit [mundoteam.org](http://mundoteam.com/).

Running
---------------------
The following are some helpful notes on how to run Mundoteam Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/mundoteam-qt` (GUI) or
- `bin/mundoteamd` (headless)

### Windows

Unpack the files into a directory, and then run mundoteam-qt.exe.

### macOS

Drag Mundoteam Core to your applications folder, and then run Mundoteam Core.

### Need Help?

* See the documentation at the [Mundoteam Wiki](https://mundoteam.info/) for help and more information.
* Ask for help on [#mundoteam](https://webchat.freenode.net/#mundoteam) on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#mundoteam).
* Ask for help on the [MundoteamTalk](https://mundoteamtalk.io/) forums, in the [Technical Support board](https://mundoteamtalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build Mundoteam Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The Mundoteam repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [MundoteamTalk](https://mundoteamtalk.io/) forums.
* Discuss general Mundoteam development on #mundoteam-dev on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#mundoteam-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
