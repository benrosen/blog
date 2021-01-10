---
title: "Random Game Ideas"
date: 2021-01-09T13:46:35-05:00
draft: false
cover:
  image: "random-game-ideas-cover.png"
---

I had been interested in making a random game idea generator for a while when I came across [sentencer][0]. Sentencer is an npm package that populates madlibs-style templates with random words. Using sentencer and [random-color-pair][1], I was able to quickly throw together a React app that could generate random game ideas. The app is hosted by AWS Amplify and Route53 at [randomideas.link][2].

The project is simple to understand. First, a template is chosen randomly from a list. Then, sentencer is used to populate the template with random words. The result is displayed on the screen. When the user taps on the page, the colors and the idea are regenerated. That's it!

This was a fun project; it was quick to come together and it's something I can easily share with my students.

If you have ideas for templates, please don't hesistate to add them to [templates.js][3] and [create a pull request][4].

[0]: https://www.npmjs.com/package/sentencer "madlibs-style sentence templating"
[1]: https://www.npmjs.com/package/random-color-pair "generate two random colors"
[2]: https://randomideas.link "random game ideas"
[3]: https://github.com/benrosen/random-game-ideas/blob/f13823e7a846aa40dded173094f2f35fa03850b1/src/templates.js "templates"
[4]: https://github.com/benrosen/random-game-ideas/pulls "pull requests"
