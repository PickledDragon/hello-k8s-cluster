# hello-k8s-cluster
Setup scripts for the RPi cluster in my so called "homelab"

# Network topology at home

![Network topology](assets/network-topology.png)

**Current Setup**
* I run a Netgear Mesh WiFi system - It isn't the best but gets the job done mostly
* Base station sits on the ground floor and I have a satellite on each floor with Wireless Backhaul
* The base station pretty much does all the heavy lifting - DCHP, DNS, Gateway, Filtering the whole shebang.
* Each satellite has 4x 1000Mbps 
* Each RPi connects to an RJ45 port on a satellite - easy peasy
* 3x Class C IPs are reserved on the base station for the RPis' Mac address 
