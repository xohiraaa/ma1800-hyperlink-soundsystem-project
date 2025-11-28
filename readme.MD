#RAVE HYPERTEXT- MA1800 Final Project

##Github Pages link:
https://xohiraaa.github.io/ma1800-hyperlink-soundsystem-project/

Rave hypertext is a small web-art piece inspired by early net.art and rave culture. Instead of a normal linear website, it works like a fragmented space you can click around: a tuner, an empty forum and a small media room.

Assets created by me:
- index.html - homepage with non-linear navigation ([TUNER], [CHAT], [TAPE])
- forum.html - fragmented forum using <details> / <summary>
- media.html - page displaying my GIMP GIF
- css/style.css - main stylesheet (layout, colour, glitch text)
- images/emoji.gif - GIF drawn + animated by me in GIMP
- All written text + page structure

Sourced material:
- audio/ tvstatic.mp3 - short static sound used in tuner.
sourced from: tvstatic sourced online: https://youtu.be/um6_q5cC154?si=X0L_526Uqhbfj6Cf 

How to open:
Either:
1. press link on readme
2. open index.html in any browser


Folder structure:
index.html
  forum.html
  media.html
  css/
  images/
  audio/

Functionality:
- non-linear navigation: the user picks a bracket link instead of being guided step-by-step.
- Internal links: `[CHAT]` and `[TAPE]` go to the other pages; each of those has a “back” link to return to the index.
- Interactive elements: audio controls, expandable forum threads, hover states on the hotspots.

Challenges:
- I joined the module late, so I had to catch up on VS Code, folder structure and GitHub at the same time.
- Getting the folders to link properly (`css/`, `images/`, `audio/`) took a few attempts because the paths kept breaking.
- Making the GIMP GIF work as an actual looping animation- found navigation a bit confusing.

Case studies from seminars that influenced the work

**JODI.org**

From the JODI examples in class, I liked how the site **refuses to behave** like a normal webpage: broken navigation, strange layouts and fake error vibes. I used this as a reference for the confusing forum and the way some of the threads feel incomplete or “deleted”. The bright colours on black and the feeling of a slightly hostile interface also come from JODI’s chaotic style.

**Olia Lialina – *My Boyfriend Came Back from the War***

Lialina’s work showed how simple HTML frames and links can create a **non-linear story**. Different panels open and close as you click, and the narrative is built out of small fragments. I mirrored this idea by using `<details>` / `<summary>` in the forum: each click reveals a tiny piece of conversation, but you never get the full story of what happened at the rave.

**MTAA – *Simple Net Art Diagram* / other early net.art**

The diagram we looked at in class emphasised the **internet itself as a medium**, not just a place to put finished work. That pushed me to treat my homepage like a weird navigation diagram instead of a standard landing page. The `[TUNER]`, `[CHAT]`, `[TAPE]` links feel more like labels in a system than “proper” buttons.

How I would extend the project with more time

If I had more time I would:

- Add more “stations” to the tuner, each with different short sound loops (e.g. jungle break, different genre sounds, crowd noise).
- Build extra forum pages, maybe with some fake moderation messages or timestamps, so it feels more like an archive you can get lost in.
- Create more hand-drawn GIMP GIFs (stickers, flyers, mascots) and scatter them around the site to make it feel denser and more chaotic.
- Experiment with very light JavaScript just for randomising which thread or GIF you land on first, to push the non-linear feeling even further.

Bibliography:

