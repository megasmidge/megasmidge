---
title: "Remote Gameplay Sucks"
date: 2023-02-07T22:25:16-08:00
draft: false
toc: false
images:
tags:
  ["Videogames",
"Linux",
"Windows",
"Dead By Daylight"]
---
Well I had a plan, but things  didn't go quite how I expected. RDP was just way too rough to play Dead By Daylight. Luckily, Steam made a tool called Steam Link that you can install on a linux machine or mobile device. It allows you to run the games from your main computer, and see the games on your remote computer. You send your keyboard/mouse from the remote computer to the main computer to play the game. The big issue here is tiny amounts of latency, which in DBD matters for skill checks. It's possible to get a sense of the delay, and adjust for it, and I think with practice it would be doable, especially for a casual survivor. Playing killer was more enjoyable.  It was tough with all the dark maps rendering light quickly enough, but it was a better experience than survivor. If I'm being honest with myself, I'm not going to play the game this way. I just get too competitive to play with a sub-par experience. For the time being, I'm going to attempt to follow youtuber G0rillaBiscuit's guide to installing DBD on Linux, and try to run it locally without the fancy GPU..... which sort of makes me wonder if I should just put Fedora on the tower.

Anyways, DBD wasn't the only game on my radar. I wanted to help my friend test the blackjack script he's been developing for FiveM. All of the existing FiveM scripts we've seen do not allow for splitting, and it's unclear if it's a true shoe/deck to be played through versus pure random-number-generator for every card pull. I tried doing via Chrome Remote Desktop, RDP, I even tried that Steam Link thing from above, but none of them could get me something smooth enough to event sit down at the blackjack table. I ended up pulling out another keyboard, mouse, and monitor, and just running both Fedora and Windows machines side by side for the day. I guess that's another reason I can't put Fedora on the tower. 

I didn't get anything done today on the "hack the box" site I've been toying around with, but I did run into a WINDOWS problem where I needed to download a certificate file (.cer) that was blocked by security download settings. Normally I would get around this by changing the file extension to .txt but that didn't work for some reason. Luckily, when it would ask me to provide a file name, I would leave that window open, and and open another file explorer, and find a temporary.crdownload stand in file waiting for me to name / the file to finish downloading, and I was able to open that temporary file with notepad. I could then take the contents of that, and copy paste it into another notepad, and save that as a .cer file. 

Final notes before I head off to bed, I saw a video about Vanilla OS which allows you to use dnf and aur and apt in separate containers all on the same machine. Looks pretty interesting! 
