# gcc-nix
This repo contains shell scripts to install GCC tools/utilities on *nix OSs. 

## TLC printing
Clone the repo and run the install script. Read instructions carefully, if CUPS is not up to date or the entered username is incorrect the installation will fail. 


If you install on MacOS, the first time you print to the black and white queue, and the color queue, you will need to update the provided print queue profiles. The update dialogue will not gain focus, check for the app in your dock. 


## MacOS VPN
Clone the repo and run the install script. This has only been tested on Mojave. 


## Linux VPN
I do not have this setup scripted. The necessary information to setup the vpn by hand is as follows, you may need to install additional packages to use the proper protocol:

Protocol: IPsec to L2TP host

Pre-shared key: gccVPNet

Gateway: StudentVPN.GCC.EDU

username: GCC\[studentemail without '@gcc.edu'] eg. `GCC\jorstadsd17`

Password: [password used for student laptop and Office365 account]
