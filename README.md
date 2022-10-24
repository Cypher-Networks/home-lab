# Home Lab cheat sheet

This GitHub will help as a form of a cheat sheet when configuring and maintaining a homelab either local or on cloud infrastucture. 

## Cloud providers: 
### [OVH](https://www.ovhcloud.com/)
Fairly cheap when wanting to host small VPS. When they have deals on for there barebones systems which are some good deals to jump on. 

Locations all around the world

### [Oracle Cloud](https://www.oracle.com/)
Oracle has a free plan where you can have a 4 Core Ampere, 24GB server. [# Amazing Free VPS (4CPU 24GB Ram) Oracle Quick Setup Tutorial](https://www.youtube.com/watch?v=g7sP33QtuxM)

Locations all around the world
 
### [Digitial Ocean](https://www.digitalocean.com/)
Digital Ocean doesn't overly care what is hosted on there systems. 

Locations all around the world

### [Hetzner](https://www.hetzner.com)
Hetzner provide a multitude of hosting options being either dedicated hardware or VPS's. When it comes to the different dedicated options they provide: [der8aur EN video](https://www.youtube.com/watch?v=5eo8nz_niiM)
*Auction contracts*
- Pros: 
	- Cheap
	- 1GB Uplink
	- High amount of ram ranging from 16 - 256 GB
- Cons:
	- Old hardware

*EX, PX, AX, SX -Line Server's*
- Pros: 
	- Modern hardware ranging from high end chipset for Ryzen all the way to Epyc server chipsets. 
	- 1GB Uplink
- Cons:
	- Expensive but competivly priced

*Hosting locations*
- Germany
	- Falkenstein
	- Nuremberg
- Finland (Powered by Green Energy)
	- Helsinki
- United States (Some of the systems are here)
	- Ashburn

Iperf3 is a tool for active measurements of the maximum achievable bandwidth on IP networks.

```shell
// Download Iperf3
sudo apt install iperf3

// Iperf3 listening on specific port of 7575
iperf3 -s -p 7575

// Iperf3 bandwidth connecting to the specific port
iperf3 -c <IP ADDRESS> -p 7575

```




