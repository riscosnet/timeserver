# TimeServer module

Version 0.01, 26/10/97

This is a simple module which when loaded will response to requests on the
udp time port with the current time in GMT, as per RFC868.

This makes the module any ideal companion to FreeTime. It acts as a server
whilst FreeTime acts as a client.

If the module cannot bind to the time port to listen for requests, it will
fail to startup. To stop your computer responding to time requests, simply
do:

    *RMKill InetTServer

Any comments, suggestions or bug reports, please contact me:

joseph@heenan.me.uk

My other programs, and updates to this are available from:

http://www.heenan.me.uk/acorn/download.html

---
Joseph Heenan, 26/10/97
