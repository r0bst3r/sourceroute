# Sourceroute
Do you have multiple nics in linux?  Ever done a ip route show and realized that linux is only using one of the nics for
outbound traffic?  This issue explained in greater detail at 
https://kindlund.wordpress.com/2007/11/19/configuring-multiple-default-routes-in-linux/.  

This python script automates the manual procedure listed on that webpage, by determining the ip information needed and
 running the iproute2 utilities to install those ip rules.
 
 Robbie Wilson
 robbie@robbiewilson.com
