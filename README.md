This repository contains the BSD _timed_ dameon and _timedc_ control program as included in the FreeBSD base system up to FreeBSD-12. It preserves the commit history of the latest FreeBSD version.

Since much improved time synchronization protocols like _ntp_ have long ago replaced _timed_, it has been removed from FreeBSD-13 and is now only available as a port (net/timed). It's only purpose is to provide time services to systems that do not support any more modern protocol.
