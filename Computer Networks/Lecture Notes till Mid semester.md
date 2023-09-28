
## Introduction

The internet : **A nuts and bolts view**
	Hosts = end systems (Computers, data centres, security camera)
	running network apps at Internet's edge

**Packet Switches** : Forward packets (Chunks of data)
	routers and switches are the two types of packet switchers
	
**Communication Links** :
	fiber, copper, radio, satellite
	transmission rate : bandwidth

**Networks** : Collection of devices, routers, Links are managed by organisation

**Internet** : "network of networks"
	Interconnected ISP's

**Protocols**: are everywhere , they control the sending and receiving of messages, eg HTTP, TCP, Wifi, a set of instructions and procedures that are standardised

**Internet Standards**: RFC (Request for commands) , IETF (Internet Engineering Task force)

The internet : A service view
**Infrastructure** that provides services to application
provides programming interface to distributed applications: hooks and connect to use internet transport service. 

##### What's a Protocol? 
#protocol
Rules for specific messages sent, transportation, received. 
All communication activity in Internet governed by protocols.

<pre> Protocol define the format, order of the messages sent and received among<br> network entities and actions taken on message transmission, receipt.</pre>


#NetworkEdge
#### Network Edge
>hosts: clients and servers
>servers often in data centres

#### Access Network, physical Media:
> wired, wireless communication links

Frequency Division Multiplexing (FDM): 
different channels transmitted in different frequency bands

HFC( hybrid fiber coax) asymmetric:
more downstream, less upstream transmission rates

DSL(digital subscriber line):
use existing telephone line to central office DSLAM
Asymmetric

Wireless access networks
Wireless local area networks (WLAN's) : small range, around 100 ft, varied speed slow
wide area cellular wireless networks : provide by mobile or cellular networks, larger range upto 10's km, 10mbps

Enterprise network is like a home network on steroids with more number of router and switching points

#hosts
##### Host : sends packet of data
>Host sending function: takes application message
>breaks into smaller chunks known as #packets, of length L bits
>transmits packets into access network at transmission rate R aka #linkBandwidth
><p>packet transmission delay = time needed to transmit L-bit packet into link= L(bits)/R(bits/sec)</p>

#links #physicalMedia

###### Physical Media
**bit**: propagates b/w transmitter/receives pairs
**physical link**: what lies between transmitter and receiver
**Guided Media**: signal propagate in solid media copper, fiber (glass fiber carrying light pulses), coax (bidirectional copper wires)
**Unguided Media**: signals propagate freely, radio(signal carried in electromagnetic spectrum, interference, noise, reflection, half-duplex)
**Twisted pair**: Two insulted copper wires 

Radio Link Types:
WiFi LAN, wide area, bluetooth(short distance), terrestrial microwave (point to point), satellite (Significant propagation delay)

#### Network Core: 
>interconnected routers
>network of networks

#packetswitching #circuitswitching 
