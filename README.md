MoIP - Morse over IP
====================
Go to the website: http://8ch9azbsfifz.github.io/moip/

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
morse code signals as UDP packets over IP. 
 
## CWCom Servers
The clients will connect to one of the servers using the CWCom protocol. 
![Architecture](/img/architecture.png?raw=true "Architecture")
The source code for a server on a Raspi can be found [here](https://sites.google.com/site/morsekob/server).

## Compatibility 
The original CWCom protocol has been extended for MorseKOB, as landline telegraphy uses 
closed circuits (latching). There are mainly two server types for moip (see below):
the original CWCom server and the MorseKOB server. Both servers are compatible using a
relay server written by Bob Denny ([source code](https://github.com/8cH9azbsFifZ/moip-relay-server/tree/master)).

# How to use?

## Client Software

| Architecture  | Name  	| License | Comment |
| :------------ |:------------ 	| :-----  | :------ | 
| Windows	| [MorseKOB 2.5](http://kob.sdf.org/morsekob/morsekob25/index.htm) 	| ? | Original MorseKOB Software by Les Kerr. [Source Code](https://sites.google.com/site/morsekob/morsekob25) |
| Browser	| [MorseKOB 3.0](http://kob.sdf.org/morsekob/morsekob30/index.htm) 	| ? | Java implementation of MorseKOB by Les Kerr |
| Linux (Python) | [MorseKOB 4.0](https://sites.google.com/site/morsekob/morsekob40) [1](https://github.com/8cH9azbsFifZ/morsekob)| ? | Python port to Raspi by Les Kerr |
| Linux, OSX, BSD | [IRMC](https://github.com/8cH9azbsFifZ/irmc)			| GPL | C implementation of morsekob|
| Arduino	| [irmc-avr](https://github.com/8cH9azbsFifZ/irmc-avr)			| GPL | arduino port|
| iOS		| [irmc-ios](https://github.com/8cH9azbsFifZ/irmc-ios) 			| GPL | ios port with support for external key using bluetooth [ble-morse](https://github.com/8cH9azbsFifZ/ble-morse) |
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

