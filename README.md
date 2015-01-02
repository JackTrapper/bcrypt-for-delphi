Bcrypt for Delphi
==================

[Bcrypt](http://en.wikipedia.org/wiki/Bcrypt) is an algorithm designed for hashing passwords, and only passwords; i.e., it's:

- not a high-speed, generic hashing algorithm;
- computationally and memory expensive;
- limited to passwords of 55 bytes.

It was first [described by Niels Provos and David Mazières in 1999](http://static.usenix.org/events/usenix99/provos/provos.pdf) for OpenBSD

It uses the Blowfish encryption algorithm, but with an "expensive key setup"
modification, contained in the function `EksBlowfishSetup`.

Created by [Ian Boyd 5/3/2012](http://stackoverflow.com/a/10441765/9990)

Public Domain
