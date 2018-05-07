DotMe Core
=====================

Setup
---------------------
[DotMe Core](http://dotme.io/wallet) is the original DotMe client and it builds the backbone of the network. However, it downloads and stores the entire history of DotMe transactions; depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run DotMe on your native platform.

### Unix

Unpack the files into a directory and run:

- bin/32/dotme-qt (GUI, 32-bit) or bin/32/dotmed (headless, 32-bit)
- bin/64/dotme-qt (GUI, 64-bit) or bin/64/dotmed (headless, 64-bit)

### Windows

Unpack the files into a directory, and then run dotme-qt.exe.

### OSX

Drag DotMe-Qt to your applications folder, and then run DotMe-Qt.

### Need Help?

* See the documentation at the [DotMe Wiki](https://en.bitcoin.it/wiki/Main_Page) ***TODO***
for help and more information.
* Ask for help on [BitcoinTalk](https://bitcointalk.org/index.php?topic=2186812.0) or on the [DotMe Forum](http://forum.dotme.io/).
* Join one of our Slack groups [DotMe Slack Groups](https://dotme.io/slack-logins/).

Building
---------------------
The following are developer notes on how to build DotMe on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The DotMe repo's [root README](https://github.com/dotmeproject/dotme/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/) ***TODO***
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources

* Discuss on the [BitcoinTalk](https://bitcointalk.org/index.php?topic=2186812.0) or the [DotMe](http://forum.dotme.io/) forum.
* Join the [DotMe-Dev](https://dotme-dev.slack.com/) Slack group ([Sign-Up](https://dotme.herokuapp.com/)).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
