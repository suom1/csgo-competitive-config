# CS:GO Competitive Serverconfigs

When you're going to set up a CS:GO server for your local CS:GO LAN or an online tournament, this problem always comes up. What CS:GO config should be used for the tournament?
  
The combination of these configs should solve your problem. The configs are built for usage in a CS:GO Major based on a rulebook ([link](https://github.com/ValveSoftware/csgo/blob/main/major-supplemental-rulebook.md)) provided by Valve. The config works without any other tournament system, but in our case it has been used with [eBot](https://github.com/deStrO/eBot-CSGO).  
  
There are a few settings that are not in the rulebook, and a few that have been diverted from the rulebook (with OK from Valve). Those settings are commented in the configs.

# Installation

For the server configs, everything in the `server` directory in this repo should be placed inside the `cfg` directory where you have installed `srcds`.  
The client configurations are ment to be loaded in the client, which can be done in many different ways. We think it's easiest if you place the configs in `C:\Program Files (x86)\Steam\userdata\<ID>\730\local\cfg` (might be different if you have chosen to install Steam in different path) and then just add `+exec <config>` into your launchoptions for CS:GO.  

### Locked nicknames

Back in 2017 Valve added a [feature](https://blog.counter-strike.net/index.php/2017/10/19582/) for locking nicknames for SteamID's which is commonly used by tournament organizers. A copy of this file is also located here (mostly to make it easy for others, but also showing how the file works).  
I have created a simple script for generating these avatars, which can be found [here](https://github.com/suom1/csgo-competitive-scripts/blob/main/server/generate_avatars.sh), and simple documentation of the usage is found both in script and [here](https://github.com/suom1/csgo-competitive-scripts/blob/main/README.md).

# Tournaments
- PGL Major Stockholm 2021
- PGL Major Antwerp 2022
