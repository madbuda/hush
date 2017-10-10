HUSH 1.0.9
=============

What is HUSH?
--------------

![Logo](doc/hush/hush.png "Logo")

HUSH (formerly Zdash) is a private implementation of the "Zerocash" protocol forked from [ZCash](https://z.cash/).
Based on Bitcoin's code, it intends to offer a far higher standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata. 

This software is the HUSH node and command-line client. It downloads and stores the entire history
of HUSH transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.


**HUSH is unfinished and highly experimental.** Use at your own risk!

TEAM
----

* Axel Karlsson: [@sparkit] Community manager, general communications.
* Iolar Demartini Junior: [@demartini] Web Developer (Front End).
* David Mercer: [@radix42] Lead Developer
* Matthew Reichardt: [@mreichardt] Core Developer, Tooling
* Duke Leto: [@leto] Core Developer, Yak Shaver
* Larry Ludlow [@madbuda] Core Developer, Infrastructure 

* You can join our team too and make contributions

Slack
-----

Please feel free to join our Slack at https://slack.myhush.org/ .
There are many channels, some you might enjoy are #general, #exchanges and #mining.

Forum
-----
https://forum.myhush.org/

Installing
----------

See [INSTALL.md](https://github.com/MyHush/hush/blob/master/INSTALL.md).

Bootstrap Nodes
---------------
Choose to add any of the following bootstrap nodes, per your preferred network configuration, to speed up peer discovery. Utilize `addnode=HOSTNAME` in your `hush.conf` file.

**IPV4**
* us.madmining.club
* 183.89.226.141
* 163.172.70.26
* 76.188.211.191
* 173.212.196.148
* 78.94.32.197
* 77.78.12.89
* 78.46.88.113
* 163.172.70.26
* 192.99.3.29
* 144.76.62.229
* 163.172.64.208
* 37.187.167.145

**IPV6**
* [2607:5300:60:341d::1]
* [2001:41d0:d:691::]
* [2a02:c207:2008:8708::1]
* [2001:470:1f09:3b6:7285:c2ff:fe0e:1664]
* [2a02:908:162:67dc:225:90ff:fe50:2b9b]

**Hush on Tor**
* hushwgexvojlkuhl.onion
* ozumguh2lk6uvcc3.onion
* hushnodejbnzyvfk.onion
* hushnodexptkgea3.onion
* keyrx4lugtnya7ax.onion
* j7h7df2tylc57xeo.onion
* madminingja2ozys.onion

Deprecation Policy
------------------

This release is considered deprecated 16 weeks after the release day. There
is an automatic deprecation shutdown feature which will halt the node some
time after this 16 week time period. The automatic feature is based on block
height and can be explicitly disabled.

Where do I begin?
-----------------
As a reference a guide for joining the main Zcash network may be used:
https://github.com/zcash/zcash/wiki/1.0-User-Guide#using-zcash
Users should *not* follow this guide blindly since it applies to ZCash instead of HUSH!
The section of using the command line is relevant to HUSH.

### Need Help?

* See the documentation at the [Zcash Wiki](https://github.com/zcash/zcash/wiki)
  for help and more general information.

### Not content with command line use of HUSH?

A [HUSH GUI Wallet](https://github.com/vaklinov/hush-swing-wallet-ui) exists and is maintained by an independent developer as a separate project. Please read about the known issues and limitations before using the wallet.

License
-------

For license information see the file [COPYING](COPYING).
