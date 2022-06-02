# Network Configuration

In a perfect tournament environment, the player PC only has access to Valve's network, the local network and services.  
This will require some special firewall rules in your nework, but also special configurations in your DNS-servers.  
  
You will in this directory find guides and example configurations for setting up a locked down CS:GO player network.  
We will be using opensource products as far as possible in order to guarantee that anyone who wnat's will have as good chances to build this network.  

There are many ways this could be done different with both software and hardware, but this is how I have built multiple tournament networks.  

## Firewall

Probably the most important part of the network is the firewall, which defines the rules for internet access. I have always have the philosophy that the network should be built as simple and easy as possible and that's also how these examples will be.  

## DNS

An important part is also DNS, since we now block most of the internet we also need to make sure that the client (player PC's) wont stall when resolving addresses that are blocked by firewall. This will make the experience much smoother of the user.

We will do this by running an DNS resolver that only queries Valve domains, and potentially some internal domains.  