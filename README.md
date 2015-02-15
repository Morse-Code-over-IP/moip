MoIP - Morse over IP
====================
In analogy to voice over ip (voip) we can also do morse code over ip (moip).
A number of different approaches for CW over IP exist. Here we describe the
well-establised CWCom protocol. 
Besides a variety of other approaches exist, for example an IRC 
plugin ([CWirc](http://myspace.voo.be/pcoupard/cwirc/)), 
a [JavaScript implementation](http://morsecode.me), 
a [bandwidth-eating UDP implementation](http://hans.liss.pp.se/node/343), 
a [chat for iOS](http://pignology.net/cwwithme.html) 
or a modulated CW over IP using Mumble ([iCW](https://sites.google.com/site/icwoip/)).


An alternative implementation in C exists<ref>IRMC (Morse KOB): http://fernski.blogspot.de/2013/03/internet-relay-morsecode.html</ref> as well as a port to the ATMEL AVR Microcontroller<ref>MorseKOB for AT Mega: http://fernski.blogspot.de/2013/05/sending-morsecode-via-atmega.html</ref>. 

Besides a variety of other approaches exist, for example an IRC plugin<ref>CWirc, Pierre-Philippe Coupard: http://myspace.voo.be/pcoupard/cwirc/</ref>, a JavaScript implementation<ref>Burak Kanber: http://morsecode.me</ref>, a bandwidth-eating UDP implementation<ref>Morse over IP, Hans Liss: http://hans.liss.pp.se/node/343</ref>, a chat for iOS<ref>CW with me (iOS), Nick Garner: http://pignology.net/cwwithme.html</ref> or a modulated CW over IP using Mumble<ref>iCW: https://sites.google.com/site/icwoip/</ref>.

# CWCom Protocol
A number of different approaches for CW over IP exist. 
An early implementation has been the CWCom protocol<ref>CWCom, John Samin (VK1EME): http://www.mrx.com.au/d_cwcom.htm</ref>,
 which has been the basis for Morse KOB<ref>Morse KOB, Less Kerr: http://kob.sdf.org/morsekob/</ref>
<ref>Morse KOB 4.0, Less Kerr: https://sites.google.com/site/morsekob/</ref>,
 a ready-to-use software. 

## CWCom Servers

## CWCom Clients
Both chat programs have been written for CW exclusively and are compatible<ref>Relay server for CW communicator and morse KOB: http://morsecode.dc3.com:7890</ref><ref>Sources for the Relay Server: http://sourceforge.net/projects/morse-rss-news/</ref>. 

 An alternative implementation in C exists as well as a port to the ATMEL AVR Microcontroller. 


# What is IRMC?
IRMC stands for Internet Relay Morse Code. 
It implements the [CWCom protocol](/doc/cwcom.pdf?raw=true) 
as adopted by [MorseKOB](http://kob.sdf.org/morsekob/docs/history.pdf). 
You can try out the software in a [browser](http://kob.sdf.org/morsekob/morsekob30/index.htm) using Java.




![Hello World](/img/hello_morse.jpg?raw=true "Hello world")


# How to use?

## Client Software

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |


## Servers
| Network 	| Server	  	| Port  | Activity | 
| :------------ | ---------------:	| :---- | :------- |
| MorseKOB      | faeroes.sdf.org 	| 7890 	| [Info](http://mtc-kob.dyndns.org/info.html) [Activity](http://mtc-kob.dyndns.org) |
| MorseKOB      | morsecode.dyndns.org  | 7890	| |
| MRX CWCom     | mtc-kob.dyndns.org    |  7890	| |


*  
*  7890
*  7890
A current list of servers if provided on the [MorseKOB Website](http://mtc-kob.dyndns.org).



# References


> The following people have helped me a lot to learn the protocols and setting up test servers.
> Les Kerr -  https://home.comcast.net/~morsekob/
> Bob Denny - http://morse-rss-news.sourceforge.net/
> John Samin - http://www.mrx.com.au/


* CWCom, John Samin (VK1EME): http://www.mrx.com.au/d_cwcom.htm
* Morse KOB, Les Kerr: https://sites.google.com/site/morsekob/ and http://kob.sdf.org/morsekob/
* Relay server for CW communicator and morse KOB: http://morsecode.dc3.com:7890 
* Sources for the Relay Server: http://sourceforge.net/projects/morse-rss-news/
* MorseKOB for AT Mega, Fernan Bolando (VE4FEB): http://fernski.blogspot.de/2013/05/sending-morsecode-via-atmega.html



