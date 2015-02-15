MoIP - Morse over IP
====================
In analogy to voice over ip (voip) we can also do morse code over ip (moip).
A number of different approaches for CW over IP exist. Here we describe the
well-establised CWCom protocol (since 1998). 
Besides a variety of other approaches exist, for example an IRC 
plugin ([CWirc](http://myspace.voo.be/pcoupard/cwirc/)), 
a [JavaScript implementation](http://morsecode.me), 
a [bandwidth-eating UDP implementation](http://hans.liss.pp.se/node/343), 
a [chat for iOS](http://pignology.net/cwwithme.html) 
or a modulated CW over IP using Mumble ([iCW](https://sites.google.com/site/icwoip/)).


![MOIP](/img/kob.jpg?raw=true "MOIP")


# CWCom Protocol
The [CWCom protocol](/doc/cwcom.pdf?raw=true) (cw communicator) is an effective method for transmitting
morse code signals as UDP packets over ip. 
 
## CWCom Servers
![Architecture](/img/architecture.png?raw=true "Architecture")

Server software:
> Bob Denny - http://morse-rss-news.sourceforge.net/

## Compatibility 
The original CWCom protocol has been extended for MorseKOB, as landline telegraphy uses 
closed circuits (latching). There are mainly two server types for moip (see below):
the original CWCom server and the MorseKOB server. Both servers are compatible using a
relay server written by Bob Denny ([source code](https://github.com/8cH9azbsFifZ/moip-relay-server/tree/master)).

## CWCom Clients
Both chat programs have been written for CW exclusively and are compatible<ref>Relay server for CW communicator and morse KOB: http://morsecode.dc3.com:7890</ref><ref>Sources for the Relay Server: http://sourceforge.net/projects/morse-rss-news/</ref>. 

 An alternative implementation in C exists as well as a port to the ATMEL AVR Microcontroller. 

An alternative implementation in C exists<ref>IRMC (Morse KOB): http://fernski.blogspot.de/2013/03/internet-relay-morsecode.html</ref> as well as a port to the ATMEL AVR Microcontroller<ref>MorseKOB for AT Mega: http://fernski.blogspot.de/2013/05/sending-morsecode-via-atmega.html</ref>. 


# What is IRMC?
IRMC stands for Internet Relay Morse Code. 
It implements the as adopted by [MorseKOB](http://kob.sdf.org/morsekob/docs/history.pdf). 
You can try out the software in a [browser](http://kob.sdf.org/morsekob/morsekob30/index.htm) using Java.


# How to use?

## Client Software

| Architecture  | Name  	| License | Comment |
| :------------ |:------------ 	| :-----  | :------ | 
| Windows	| [MorseKOB 2.5](http://kob.sdf.org/morsekob/morsekob25/index.htm) 	| ? | Original MorseKOB Software by Less Kerr. [Source Code](https://sites.google.com/site/morsekob/morsekob25) |
| Browser	| [MorseKOB 3.0](http://kob.sdf.org/morsekob/morsekob30/index.htm) 	| ? | Java implementation of MorseKOB by Less Kerr |
| Linux (Python) | [MorseKOB 4.0](https://sites.google.com/site/morsekob/morsekob40)	| ? | Python port to Raspi by Les Kerr |
| Linux, OSX, BSD | [IRMC](https://github.com/8cH9azbsFifZ/irmc)			| GPL | C implementation of morsekob|
| Arduino	| [irmc-avr](https://github.com/8cH9azbsFifZ/irmc-avr)			| GPL | arduino port|
| iOS		| [irmc-ios](https://github.com/8cH9azbsFifZ/irmc-ios) 			| GPL | ios port|
| iOS & ext key	| [ble-morse](https://github.com/8cH9azbsFifZ/ble-morse)		| GPL | external interface with ble for ios |
| Windows 	| [CWCom](http://www.mrx.com.au/d_cwcom.htm)		 		| Closed Source | original cwcom software by John Samin | 


## Servers
| Network 	| Server	  	| Port  | Activity | 
| :------------ | ---------------:	| :---- | :------- |
| MorseKOB      | faeroes.sdf.org, mtc-kob.dyndns.org 	| 7890 	| [Info](http://mtc-kob.dyndns.org/info.html) [Activity](http://mtc-kob.dyndns.org) |
| MRX CWCom      | morsecode.dyndns.org  | 7890	| [Activity](http://morsecode.dyndns.org) |
| Relay Server 	| N/A 			| N/A 	| [Activity](http://morsecode.dc3.com:7890) |

# References
* Morse KOB, Les Kerr: https://sites.google.com/site/morsekob/ and http://kob.sdf.org/morsekob/
* CWCom, John Samin (VK1EME): http://www.mrx.com.au/

