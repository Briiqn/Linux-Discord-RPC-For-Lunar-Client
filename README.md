# Linux-Discord-RPC-For-Lunar-Client
Uses pypresence and xdotool to display what version and state of lunar client


install xdotool via your package manager and pypresence from "pip install pypresence"

This can be added as a helper script for Youded Bytes Lunar Client QT by adding the runrpc script first and then the Killrpc script second

Youded Byte's Lunar Client QT Fork --> https://github.com/Youded-byte/lunar-client-qt

This also works if the scripts Killrpc and runrpc are added to startup but it wont work as well as using Youded Byte's Lunar Client QT fork

I also made a copy of python3.10 and renamed it cpy so it doesn't killall python processes even though I could of got the process id of the python scripts and kill those indivually but I'm trying to get this out as quick as possible, so just do 'sudo cp /usr/bin/python3/ /usr/bin/cpy/' to make the cpy application
