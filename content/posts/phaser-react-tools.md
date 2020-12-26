---
title: 'Phaser React Tools'
date: 2020-12-26T09:22:31-05:00
draft: false
cover:
  image: 'phaser-react-tools-cover.png'
---

I spend a lot of time at work helping people who are new to game development. There are many excellent options for beginners who are interested in creating games, from [Scratch][0] to [processing][1] to [Unity][2]. These days, one of my favorite ways to make games is with [Phaser][3]. Phaser is easy to set up, and it has [lots of great examples][4] to work from. Phaser also has plenty of convenient features that make other game engines (looking at you, Unity) seem kind of clunky in comparison. And, because Phaser is part of the JavaScript ecosystem, the possibilities for integrating your Phaser game with other frameworks are endless.

One thing that I _don't_ love about Phaser is the system for building user interfaces. It's not that Phaser's UI system is bad - it's just not as good as more mature frameworks for UI development, such as [React][5]. Unfortunately, Phaser and React don't play very nicely together by default. In fact, they are described as [oil and water][6] on the Phaser site.

To help mitigate the challenge of mixing these two very different frameworks, I've published a simple toolkit called [phaser-react-tools][7]. The package contains one React component, a context, and some hooks. Using these simple tools, you can embed a Phaser game in your React app, build a React UI overlay for your Phaser game, and send events back and forth between Phaser and React with ease.

I enjoyed the process of packaging and publishing these tools. I bootstrapped the project with [create-react-library][8], and I used [jsdoc][9], Braintree's [jsdoc-template][10], and [GitHub pages][11] to generate and host [the documentation][12]. Testing is made possible by [jest][13].

This is the second "module" that I'm releasing as part of my ongoing multiplayer chess project. The first module was a pack of [free pixel art chess sprites][14]. The next module will likely be an npx script in the vein of [create-react-app][15] for initializing Phaser + React apps.

[0]: https://scratch.mit.edu/ 'If you think you know how to program, try Scratch.'
[1]: https://processing.org/ 'Processing'
[2]: https://unity.com/ 'Unity'
[3]: https://phaser.io/phaser3 'Phaser'
[4]: https://phaser.io/examples 'Phaser examples'
[5]: https://reactjs.org/ 'React'
[6]: https://phaser.io/news/2019/07/ion-phaser 'oil and water'
[7]: https://www.npmjs.com/package/phaser-react-tools 'literally the greatest npm package ever created... probably'
[8]: https://www.npmjs.com/package/create-react-library 'like create-react-app, but different'
[9]: https://jsdoc.app/ 'JavaScript documentation tools'
[10]: https://github.com/braintree/jsdoc-template 'a template for jsdoc'
[11]: https://pages.github.com/ 'GitHub pages'
[12]: https://benrosen.github.io/phaser-react-tools/ 'the docs'
[13]: https://jestjs.io/ 'JavaScript testing framework'
[14]: https://benrosen.github.io/posts/pixel-art-chess-pieces/ 'blog post on pixel art chess pieces'
[15]: https://www.npmjs.com/package/create-react-library 'like create-react-libarary, but different'
