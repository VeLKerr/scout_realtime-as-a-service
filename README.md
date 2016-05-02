## scout_realtime-as-a-service

Script for making scout_realtime application as a service

1. Copy the ```scout_realtime``` file to the ```/etc/init.d``` directory.

2. Run ```sudo update-rc.d scout_realtime defaults```.
If you got some errors, remove previous links using ```sudo update-rc.d scout_realtime remove```.

Now, the scout_realtime will start automativally on machine boot.

