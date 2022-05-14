# CS:GO Competitive Configs

When you're going to set up a CS:GO server for your local CS:GO LAN or an online tournament, this problem always comes up. What CS:GO config should be used for the tournament?
  
The combination of these configs should solve your problem. The configs are built for usage in a CS:GO Major based on a rulebook ([link](https://counter-strike.net/csgo_major_supplemental_rulebook)) provided by Valve. The config works without any other tournament system, but in our case it has been used with [eBot](https://github.com/deStrO/eBot-CSGO).  
  
There are a few settings that are not in the rulebook, and a few that have been diverted from the rulebook (with OK from Valve). Those settings are commented in the configs.

# Installation

In this setup all config files and nicknames.txt should be installed in the `cfg` directory. 

### Locked nicknames

Back in 2017 Valve added a [feature](https://blog.counter-strike.net/index.php/2017/10/19582/) for locking nicknames for SteamID's which is commonly used by tournament organizers. A copy of this file is also located here (mostly to make it easy for others, but also showing how the file works).  
I have created a simple script for generating these avatars, which can be found [here](https://github.com/suom1/csgo-competitive-scripts/blob/main/server/generate_avatars.sh), and simple documentation of the usage is found both in script and [here](https://github.com/suom1/csgo-competitive-scripts/blob/main/README.md).

# Tournaments
- PGL Major Stockholm 2021
- PGL Major Antwerp 2022
