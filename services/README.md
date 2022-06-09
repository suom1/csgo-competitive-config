# Services

There are a few different services needed to make running an event smooth. This part of the repo will show how I have done it on the events I have worked.  

## Config and driver distribution

Since all players submits their configs and drivers before the tournament starts in order to have the configs and drivers checked you will need a way to distribute these in the tournament network when the machines are in a network without internet.  
  
We have chosen a read-only samba share without any authentication on it. With this however comes a few things that needs to be changed on the player machines when running Windows 10 or 11. Since shares with no authentication has been definied as `insecure` since Windows 10, you will find the documentation for that [here](https://github.com/suom1/csgo-competitive-config/tree/main/client/README.Shares.md).

## DNS

