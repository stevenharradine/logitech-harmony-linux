# logitech-harmony-linux
Instructions for setting up and using your harmony remote in linux.  Based on these instructions http://openattitude.com/2011/01/27/how-to-set-up-a-harmony-remote-using-linux/ but had to do more research into getting it to work so here is everything you need in one place.

## Install Prerequisites
```sudo ./prerequisites.sh```

## Confirm remote connectivity
1. Plug in remote
2. ```sudo ./connect-remote.sh```

## go to logitech website for legacy support
http://members.harmonyremote.com/EasyZapper/UserHome.asp

## configure your remote in the web interface

## update your remote
1. Click "Update My Remote"
2. Click `Next` (Connectivity.Hex will download)
3. ```sudo congruity Connectivity.EZHex``` and follow on screen prompts
4. Click `Next` (Update.Hex will download)
5. ```sudo congruity Update.EZHex``` and follow on screen prompts
6. On the site click `Yes` and `Next`

## Your remote should be programmed
