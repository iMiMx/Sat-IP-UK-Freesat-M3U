# Sat-IP-UK-Freesat-M3U
Minus 'rubbish' channels, music, radio, kids, etc

- RTSP (UDP) direct to Channels DVR, tuning was slow
- HTTP direct to Channels DVR, tuning was as fast as RTSP via TVHeadend
- satip:// (UDP, calls RTSP to the Sat>IP server) direct to Channels, as fast (if not slightly faster) than RTSP via TVHeadend

satip:// URLS are the way forward for me:

"Also it would be better to start using satip:// in the urls instead of rtsp://. SAT>IP boxes don't use proper RTSP, so satip:// url makes it more clear to the client that it should use the specific SAT>IP version of RTSP protocol."

https://community.getchannels.com/t/sat-ip-support/7449/142?u=imx
