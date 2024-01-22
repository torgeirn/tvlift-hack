# TV-Lift Hack
Trying to hack my tv-lift into HomeAssistant

## Background info for this project
This project started with me having a TV-Lift with a stupid RF-remote that cannot be replaced by my Logitech Harmony remote. I then watched [Level1Techs video about the Sonoff RF-Bridge](https://www.youtube.com/watch?v=Si2vt6fCTUY) and thought that this was the solution to all of my problems. I proceeded to buy a Sonoff RF-Bridge, started the tutorial. As soon as I opened the device, I discovered that I had a new HW-revision. HW-hacking of this kind was way above my skill level. I got annoyed, and forgot about the whole thing.
Until i stumbled across this [Youtube video](https://youtu.be/k-FLN1cM4jk?si=Mh5JG8W0j0KNtHbd) explaining the same process using the new HW-revision of the Sonoff bridge. Finally I would finish this project!
It was first when I got to the point in the video where I was going to capture the commands from my remote that I discovered that RF is not RF. The Sonoff bridge operates at 433MHz as advrtized. The only RF i knew at the time. The tv-lift remote operates at 2.4GHz. The manual specifies "RF-remote", so I guess it was also as advertized.

This left me back at square one whithout a plan, but enough built up anger at my tv-lift that I swore to make it work some how.

In the meantime, I had gotten better at HomeAssistant, and had started tinkering with ESP32.
This is my new plan. I will try to control the tv-lift using ESPHome.

## Requirements for the ESPHome based solution
1. Will use ESPHome and an  ESP32 NodeMCU board.
2. The remote will not be modified.
3. Board must attach to the tv-lift in paralell with the remote.
4. Attachment of board must be non-destructive and possible to remove at a later stage.

## Writeup of this project
Details about the tv-lift, both usermanuals and my reverse engineering steps, can be found in [TV-lift](./TV-lift/)

If you want to jump directly to the solution, go to [Solution](./Solution)
