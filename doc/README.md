Gymnasium Core
==========

This is the official reference wallet for Gymnasium digital currency and comprises the backbone of the Gymnasium peer-to-peer network. You can [download Gymnasium Core](https://www.gymnasium.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run Gymnasium Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/gymnasium-qt` (GUI) or
- `bin/gymnasiumd` (headless)

### Windows

Unpack the files into a directory, and then run gymnasium-qt.exe.

### macOS

Drag Gymnasium Core to your applications folder, and then run Gymnasium Core.

### Need Help?

* See the [Gymnasium documentation](https://docs.gymnasium.org)
for help and more information.
* Ask for help on [Gymnasium Discord](http://staygymnasiumy.com)
* Ask for help on the [Gymnasium Forum](https://gymnasium.life/forum)

Building
---------------------
The following are developer notes on how to build Gymnasium Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Gymnasium Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* See the [Gymnasium Developer Documentation](https://gymnasium.readme.io/)
  for technical specifications and implementation details.
* Discuss on the [Gymnasium Forum](https://gymnasium.life/forum), in the Development & Technical Discussion board.
* Discuss on [Gymnasium Discord](http://staygymnasiumy.com)
* Discuss on [Gymnasium Developers Discord](http://chat.gymnasiumdevs.org/)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [gymnasium.conf Configuration File](gymnasium-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [I2P Support](i2p.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [PSBT support](psbt.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
