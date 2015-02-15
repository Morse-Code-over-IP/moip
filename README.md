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

An alternative implementation in C exists<ref>IRMC (Morse KOB): http://fernski.blogspot.de/2013/03/internet-relay-morsecode.html</ref> as well as a port to the ATMEL AVR Microcontroller<ref>MorseKOB for AT Mega: http://fernski.blogspot.de/2013/05/sending-morsecode-via-atmega.html</ref>. 


# What is IRMC?
IRMC stands for Internet Relay Morse Code. 
It implements the [CWCom protocol](/doc/cwcom.pdf?raw=true) 
as adopted by [MorseKOB](http://kob.sdf.org/morsekob/docs/history.pdf). 
You can try out the software in a [browser](http://kob.sdf.org/morsekob/morsekob30/index.htm) using Java.




![Hello World](/img/hello_morse.jpg?raw=true "Hello world")


# How to use?

## Client Software

| Architecture  | Name 		| Authors | License | Link |
| :------------ |:------------ 	| :-----  | :------ | :--- |
| Windows	| MorseKOB 2.5 	| Kerr	  | ? | [MorseKOB 2.5](http://kob.sdf.org/morsekob/morsekob25/index.htm) |
| Browser	| MorseKOB 3.0 	| Kerr	  | ?  | [MorseKOB 3.0](http://kob.sdf.org/morsekob/morsekob30/index.htm) |
| Linux, OSX, BSD | IRMC	| Bolando (VE4FEB) & Ziegenhain (DG6FL)	| GPL | [IRMC](https://github.com/8cH9azbsFifZ/irmc) 	|
| Arduino	| IRMC-AVR	| Bolando (VE4FEB) & Ziegenhain (DG6FL) | GPL | [irmc-avr](https://github.com/8cH9azbsFifZ/irmc-avr)	|
| iOS		| irmc-ios 	| Ziegenhain (DG6FL)	| GPL | [irmc-ios](https://github.com/8cH9azbsFifZ/irmc-ios)	|
| iOS & ext key	| ble-morse	| Ziegenhain	(DG6FL) | GPL | [ble-morse](https://github.com/8cH9azbsFifZ/ble-morse) |
| Windows 	| CWCom		| Samin (VK1EME)	| Closed Source | [CWCom](http://www.mrx.com.au/d_cwcom.htm) | 


## Servers
| Network 	| Server	  	| Port  | Activity | 
| :------------ | ---------------:	| :---- | :------- |
| MorseKOB      | faeroes.sdf.org, mtc-kob.dyndns.org 	| 7890 	| [Info](http://mtc-kob.dyndns.org/info.html) [Activity](http://mtc-kob.dyndns.org) |
| MRX CWCom      | morsecode.dyndns.org  | 7890	| [Activity](http://morsecode.dyndns.org) |


# References


> The following people have helped me a lot to learn the protocols and setting up test servers.
> Les Kerr -  https://home.comcast.net/~morsekob/
> Bob Denny - http://morse-rss-news.sourceforge.net/
> John Samin - http://www.mrx.com.au/


* Morse KOB, Les Kerr: https://sites.google.com/site/morsekob/ and http://kob.sdf.org/morsekob/
* Relay server for CW communicator and morse KOB: http://morsecode.dc3.com:7890 
* Sources for the Relay Server: http://sourceforge.net/projects/morse-rss-news/
* MorseKOB for AT Mega, Fernan Bolando (): http://fernski.blogspot.de/2013/05/sending-morsecode-via-atmega.html



