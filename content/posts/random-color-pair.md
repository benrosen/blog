---
title: "Random Color Pair"
date: 2021-01-01T13:32:50-05:00
draft: false
cover:
  image: "random-color-pair-cover.png"
---

Here's [a tiny little script][0] that gives you two colors: one dark and one light.

I needed an easy way to create pairs of colors that were distinct enough to be used for foreground and background colors.

Right now, this package uses [randomcolor][1] to generate colors. `randomcolor` allows you to specify luminosity when generating colors, so I just generate one 'light' color and one 'dark' color and return the results.

This was a super quick and easy project to throw together, and it was a good way to practice testing, documenting, and publishing npm packages. Plus, it's useful for [another project][2] I'm working on.

In the future, I could see improving this to make the color pairs more pleasing. But for now, this'll do just fine.

[0]: https://www.npmjs.com/package/random-color-pair "random-color-pair"
[1]: https://www.npmjs.com/package/randomcolor "randomcolor"
[2]: https://github.com/benrosen/random-game-ideas "random-game-ideas"
