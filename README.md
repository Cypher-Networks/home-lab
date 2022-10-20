# Home Lab cheat sheet

This GitHub will help as a form of a cheat sheet when configuring and maintaining a homelab either local or on cloud infrastucture. 




## Cloud providers: 
### [OVH](https://www.ovhcloud.com/)



### [Oracle Cloud](https://www.oracle.com/)

 
### [Digitial Ocean](https://www.digitalocean.com/)


### [Hetzner](https://www.hetzner.com)
Hetzner provide a multitude of hosting options being either dedicated hardware or VPS's. When it comes to the different dedicated options they provide:
*Auction contracts*
- Pros: 
	- Cheap
	- 1GB Uplink
- Cons:
	- Old hardware but

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
- Finland
	- Helsinki
- United States
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




