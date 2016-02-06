---
layout: post
title:  "Use the Frameworks Tools"
date:   2016-02-05
categories: peripheral code stuff
---

- Struggled with http request timeouts in game
- Tried timing out with executor service (java.concurrent)
- Never threw the timeout exception no matter what I did
- Turns out, Gdx's http service has a setTimout Function
- Maybe I should read the docs more (who does that?)
- Use the frameworks tools
