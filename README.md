# tvlift-hack
Trying to hack my tv-lift into HomeAssistant
This project started with me having a TV-Lift with a stupid RF-remote that cannot be replaced by my Logitech Harmony remote. I then watched Level1Techs video about the Sonoff RF-Bridge [Youtube](https://www.youtube.com/watch?v=Si2vt6fCTUY) and thought that this was the solutioon to all of my problems. I proceeded to buy a Sonoff RF-Bridge, started the tutorial and as soon as I opened the device I discovered that I had a new HW-revision. HW-hacking of this kind was way above my skill level. I got annoyed, and forgot about the whole thing.
Until i stumbled across this video [Youtube](https://youtu.be/k-FLN1cM4jk?si=Mh5JG8W0j0KNtHbd). Finally I would finish this project!
It was first when I got to the point in the video where I was going to capture the commands from my remote that I discovered that RF is not RF. The Sonoff bridge operates at 433MHz as advrtized. The tv-lift remote operates at 2.4GHz. The manual specifies "RF-remote", so I guess it was also as advertized.


