PepeMint
=============

Setup
---------------------
PepeMint is a PepeMint client and it builds the backbone of the network. However, it downloads and stores the entire history of PepeMint transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download PepeMint, visit [pepemintmore.org](https://pepemint.me/).

Running
---------------------
The following are some helpful notes on how to run PepeMint on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/pepemint-qt` (GUI) or
- `bin/pepemintd` (headless)

### Windows

Unpack the files into a directory, and then run pepemint-qt.exe.

### OS X

Drag PepeMint-More.app to your applications folder, and then run PepeMint-More.

### Need Help?

* See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.
* Ask for help on [#pepemint](http://webchat.freenode.net?channels=pepemint) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=pepemint).
* Ask for help in [PepeMint room](https://gitter.im/PepeMint_Hub) on Gitter.
* Ask for help in [/r/pepemint/](https://nm.reddit.com/r/pepemint/) on Reddit.
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [PepeMint topic](https://bitcointalk.org/index.php?topic=3017838.new#new).

Building
---------------------
The following are developer notes on how to build PepeMint on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The PepeMint repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [PepeMint topic](https://bitcointalk.org/index.php?topic=3017838.new#new).
* Discuss PepeMint development in [PepeMint room](https://gitter.im/PepeMint_Hub) on Gitter.
* Discuss PepeMint development in [PepeMint team](https://keybase.io/team/pepemint) on Keybase.

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
