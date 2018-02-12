# p910nd
p910nd is a small printer daemon intended for diskless platforms that does not spool to disk but passes the job directly to the printer. Normally a lpr daemon on a spooling host connects to it with a TCP connection on port 910n (where n=0, 1, or 2 for lp0, 1 and 2 respectively). p910nd is particularly useful for diskless platforms. [Common Unix Printing System](http://www.cups.org/) (CUPS) supports this protocol, it's called the AppSocket protocol and has the scheme socket://. [LPRng](http://www.lprng.com/) also supports this protocol and the syntax is lp=remotehost%9100 in /etc/printcap.

p910nd is released under the GPLv2.

[Sourceforge project page](http://sourceforge.net/projects/p910nd/)

Last updated 2014-01-11 by Ken Yap
