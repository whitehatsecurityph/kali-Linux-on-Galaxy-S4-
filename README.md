# kali-Linux-on-Galaxy-S4-
How to Install kali linux on android device
1. Download Linux Deploy from PlayStore

2. Open it and go to settings

3. Selection Distribution: Kali and leave everything else as default, except Disk Image Size, which you should use 7128mb instead of Automatic.

3a. Normally it automatically finds your resolution, but you can change it on this page. (One of the last items.)

4. Then select Install

4a. [IMPORTANT] Be sure to be connected to a Wi-Fi network, otherwise 1.4GB will be downloaded from your Mobile Network.

4b. The downloading time is quite long, and you can't lose connection through that, otherwise the .img will be corrupted.

5. Once you see <<< end: installation on the app, download your favorite VNC client and set-up the following configurations:

{Quote:
IP/Host: localhost or 127.0.0.1
Port: 5900
Password: changeme}

6. You will notice that there's no tools avaliable, open LXTerminal (From the dropup icon of Kali) then type:

{Quote:
sudo apt-get update}

and 
{Quote:
sudo apt-get upgrade}

Those are minor commands, to really install the tools see next step

7. Type 
{Quote:
sudo apt-get install kali-linux -yq}

And wait for the full installation to complete, after it's sucesfully done it's good to go!

#whitehat
#ethical hackers ph
