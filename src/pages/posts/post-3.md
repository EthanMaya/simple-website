---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Roadmap for website'
pubDate: 2022-07-01
description: "My plan for the website and how I'm going to implement it."
author: 'Ethan Maya'
image:
    url: 'https://docs.astro.build/assets/rose.webp'
    alt: 'The Astro logo on a dark background with a pink glow.'
tags: ["website"]
---

### Stuff to do before going live.
### Content

Reformat content in;

**Computer Science**, add content

Can use git: used it in all my projects maybe put it as a tag in projects that use it. 
several years experience using linux: used it since I was 15, my first computer was a pi 400. when i got my laptop I dual booted mint and win 10 on it. my 3 backup laptops used mint. My workstation uses nixos.
used virt-manager for running vms: run malware on a vm for testing, run windows in a vm for windows apps. also used winapps for integration into the linux host.
created vm for lea: a coursemate didn't have a powerful enough pc to run software over the summer so I made a vm on my workstation, added her to my tailnet and set up a vnc server so she could connect to a desktop with tigervnc.
used rdp, sunshine moonlight: remoted into my workstation using rdp, then switched to sunshine moonlight and run it headless? not connected to a screen but with a desktop.
used vnc: for swansea uni race engineering dash, I set up one of my computers to have a vnc server, and added it to my tailnet. Then the dashboard was connected to the pc allowing me to upload code remotely and placed so I could look through the camera to see what the dash looked liked.
used java fx for creating app: Not sure if it's actually an app, and it didn't actually work. The Computer Science Society was doing projects for working in teams and boosting resumes. there was one year three, two year twos and me a year one. we were going to make a basic game which would be 2d and be a city builder. The 3 year made the base template and I coded up a basic grid, but the two year two's stopped contributing and the project fizzled out. The other javafx i did was a coursework so I don't know whether I can put it.
tailscale: I regularly use tailscale on all my computers so i can ssh into them.
docker compose: used for the backend of winapps before switching to virt-manager.
github: simple-website, a mirror for the website this is running on. nixos_dotfiles, config files for workstation, swansea-dash, code for dashboard. 
wake on lan: my workstation does wol so I can turn it on remotely. 

Should I put any of my courseworks/am i actually allowed to by the uni?

Bitburner: hacking game where you "hack" servers to make profit. written in javascript.
GCHQ: I completed all the challenges for their scholarship but failed the interview.
Leet/Neetcode: I made a repo which allows me to put the test in json, then run the code and print out which tests it passes and fails. Currently only fully works in python but I have bits which can be run in java and c++. the plan is for it to be able to run python, java, javascript, c, c++, c#, go, php, rust and possibly some other ones.

The Personal website and hosting feels a bit weird how it's done, because of how there's the website and it's repo, and then my nixos stuff which isn't really a part of it other than also being on github. this is some info on the website if it helps. This website: uses cloudflared tunnel to route traffic to the pi. The pi has a git server on it, so when i push, i push to github and the pi at the same time, allowing me to automatically update my website with a git hook. The website uses Astro, the theme was got from a template called codefolio but then customised to have a blog, rss, and different theme (although I'll probably take out the blog, which makes the rss pointless?)
Skills & Tools

Programming Languages: Python, Java, C/C++, JavaFX.
Systems & Platforms: Linux (Mint, Ubuntu, NixOS), Raspberry Pi, PlatformIO, Espressif IDF.
Virtualisation & Networking: virt-manager, Docker Compose, Tailscale, VNC, RDP, Sunshine/Moonlight, Wake-on-LAN.
Development Practices: Git/GitHub (used across all projects), collaborative development, remote testing.
Other Tools: Squareline Studio, LVGL, Arduino, CAN bus, 3D printing, CAD.
“Linux configuration management (NixOS dotfiles repo, reproducible system setup).”


Can use git. several years experience using linux. 
used virt-manager for running vms, created vm for lea.
used rdp, vnc, sunshine moonlight.
used java fx for creating app.
What else should i put in, what are employers looking for?
The Linux/git/VMs/Raspberry Pi stack
like your JavaFX app, VM work, glider project, yacht designs, etc.,

Should I put any of my courseworks

**Aerospace**, work out what's relevant, and what my aim is., get rid of Aerospace and have it in personal projects
rename Personal projects to Things I've done?

show that i have physical experience, as well as a good theoretical understanding.

glider project: got 20 students involved in making an ai glider for slope soaring. project failed.
yacht designs: I did a lot of design, I knew multiple yacht designers, never actually made anything.
Aerospace: last semester, I unofficially took a masters course in advanced aerodynamics. However I didn't get any qualification and wouldn't say I am confident in it.
When I was 12, I did gliding in the cotswolds, did this until I was 14, when I switched to paragliding. I flew mainly on Dartmoor and along the coast.
built a simple catamaran (the cat) with a square sail when I was 8, using 10 dartmoor water bottles for the bouyancy. This was upgraded over the years until it had a lug rig and jib, and a the hull size was increased.
sailing: I officially learnt to sail when i was 9 and mainly sailed a laser 2 singlehanded using a trapeze.
I restored a boat (international moth) for sailing. glassfibred it and repaired the mast. Never got it to a state that I could sail it though and it's now in my garden.
White water kayaking: did white water kayaking when I was 10, did the loop, lower, lower lower. (people always assume because of age I was doing it with an adult in the boat but I wasn't it was singlehanded, don't know how to say that)
sailed aboard a classic yacht sibyl of cumae a couple of times, just crew though.

played the violin: started when I was 8, played twice in the National Children's Orchestra of Great Britain.


**Personal Projects** sort of for anything I don't think fits in either Compsci or Aerospace

sailed a lot, designed a lot of yachts, did windsurfing, kite buggying, model flying, Rocketry, Cad

animation, blender, music

**Blog** I don't know, why do I have a blog. Turn it into a diary for typing, say what I've been up to each week.

**About** Life story. why i got into computer science

**Contact Details** email address, github, discord.


### CV
worked at morrisons, sky sprouts. did 70 hours a week, worked on click and collect, then worked on srp. I also helped around the store in the bakery,
kitchen, on the shop floor working fresh, frozen, and. also worked the deliveries in the night



### Icons.

Change icons for;

Aerospace


### Page layouts.

Blog needs to be formatted

Contact details needs to to be formatted




### CSS

Understand styling

change styling so the default colour is white instead of grey.

Some things affected are ```<ol> <p>, <h4>```

Need to change colour of clicked and unclicked links.


### After going Live.

### Page layouts
Change About to have less space between paragraphs

### Icons

blog, computer science, contact details

### Site Changes

Change back button to say where it's going.

Change back from blog to either go to all tags or blog

Make back button take up less vertical space

When using back button, it automatically goes to the top of the page, look for a way to go to where you were.

Make all projects link somewhere.

Way to show pictures and videos.





find a better way to do lightmode, which doesn't have flashing.


### To the Future.

Look into typing checker.

access part of a website, makes a vm spin up and allows you to run code on it? Very big security risk. use quacamole to send it.

make email server, and use custom domain for email ethan@ethanmaya.co.uk

Make a way for people to make their own blogs, leave comments. put a word filter so it isn't too bad. look into using simple ai to scan the messages

