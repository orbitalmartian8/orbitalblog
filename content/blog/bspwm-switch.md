---
title: Why I Chose To Switch To BSPWM
description: Wayland may be the future, but it isn't the present, things are buggy and need a lot of work before they are ready for daily use.
date: 2023-08-27
tags:
 - BSPWM
 - Wayland
 - Review
---

## Wayland may be the future, but it isn't the present, things are buggy and need a lot of work before they are ready for daily use.

Over my now two years of using Linux, I've used my fair share of Window Managers and Desktop Environments. I've also had plenty of time to tinker with both XOrg and Wayland as my display server, and after a month or 4 running pure Wayland, I'm going back to X, because it runs much smoother and has less crashes and bugs. I have recently started using my Fedora 38 laptop as a gaming rig, I've used many WM/DE over the month or two I've been in this situation, I've used both Wayland and X11 and I had more crashes and experienced more bugs whilst on the Wayland side, than the X11 side. I have used BSPWM before, and it was my main WM for a long while, but I moved away in favour of Hyprland and Sway as Wayland Compositors.

### What's The Issue With Wayland
Wayland is awesome and all but it is far from ready, from my two to five month experience of Wayland, across many DE and compositors. There are many bugs and glitches that I have faced over the time, and these have added up to many a crash that I have grown to find really annoying, these have caused me to push my way back into the XOrg space.

Wayland as a whole is a young project, and has many issues, certain apps and services don't work under Wayland. Things such as screen sharing and audio sharing, as a content creator these were not a problem during my hiatus but now I'm getting back into making content, it is drawing into a bigger issue. Another issue I have been having is that it is quite laggy, and though this may be down to my old hardware, but still it poses a problem.

This slow downs have caused me to have moments where the whole system locks up and I eventually have to manually restart it, I know this is not recomended but I became desperate. This became such a pain to me that I figured, lets try on X and low and behold, the crashes stopped.

So I made the jump...

### Why BSPWM?
Remembering back to my time in various WMs over the years I've been on Linux, I rekindled an old flame for BSPWM, it's amazing and my workflow fit into it. My initial thoughts after switching back to BSPWM, was how easy the configuration is and how easy it was to make it work. I fell back in love with the whole thing and started getting my basic setup, all up and running.

Although BSPWM hasn't seen any commits in the master branch since April 5th this year, which to me seems it may have been abandoned, the experience has been stable and super fast. I've still got some tweaking to do but I'll have it done soon and once it's basically done and stable, I'll push my dotfiles to my [Codeberg dotfiles repo](https://codeberg.org/orbitalmartian/dotfiles).

### Conclusion
Now with my reasons explained and my thoughts pulled out of my brain by the magic of a keyboard, I'm going to sign off for now, I hope you enjoyed this post, I sure enjoyed the inspiration stages for this post so have a great rest of your day, morning, afternoon, evening, or night. If you made it to the end, leave a 🐬 in the comments down below, and let me know your thoughts down below.

#### Links:
- [Wayland](https://wayland.freedesktop.org/)
- [BSPWM](https://github.com/baskerville/bspwm)
- [Ny Codeberg Dotfiles Repo](https://codeberg.org/orbitalmartian/dotfiles)
