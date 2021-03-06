# Plink Plonk
A minimal auditory debugger for web pages.

## Installation
There are two possible ways to install this extension:

### Easy way

From the Chrome Web Store - TBD / Waiting for the Chrome store review. Meanwhile, use the manual installation below

### Manually or if you wish to contribute

Clone or download this project

Go to your extensions page: chrome://extensions/

Check the "Developer mode" box in the top right

Click on the "Load unpacked extension..." button from the dropdown and point it to the unzipped extension directory that you just downloaded/cloned.

## Screenshot

![Screenshot][screenshotlink]

## Goal/Story

The original source code is [over there][original-script]. I didn't like the idea at first because I didn't find it useful, then another user (@SeriousM) [suggested to make it trigger on network activity too][network-feature-suggestion].

That was more interesting. I did some research on this and figured it's possible, so I turned it into a Chrome extension.

Initially, I decided to leave out the dom event listener feature but it's been a while since I created a Chrome extension and I felt rusty. So the pragmatic programmer in me decided to start with this feature and then add the new one later.

As soon as it became an extension, I realized how useful this feature actually is... not for debugging, but for monitoring and maybe even reverse engineering. Not just your own website, but any website.

It was interesting to hear elements being created on my Quora reading list even though I wasn't doing anything. It was also interesting to hear the Plink Plonk go everytime the visibility of the typing indicator of the online Github editor toggled.

I'll be working on it every Sunday and will accept any useful pull request.

## Features

- Fires on every dom changes
- Allows to quickly deactivate it instead of removing it from Chrome - TBD
- Fires on every network request - TBD
- Allows to select what to hear sound for (Network or Dom Changes) - TBD
- Allows to update delay and frequency on the fly - TBD
- Allows to make it sound more futuristic (by making the pitch of a single oscillator longer) - TBD
- Display a sticky pulsing circle on the page to provide sound visualization - TBD
- Allows to select whether you want sound visualization - TBD
- Port it to Firefox - TBD

## TODO

- Add a license
- Create a better icon/logo

## Credits

Props to the author of [the original script][original-script]: [@tomhicks][og].

Icon and logo made with the elegant [Pixlr][pixlr] tool. I could do better, but I was going fast.

If you have any questions, just [send me a tweet][twitter]. For improvement suggestions or bugs, [open an issue][issues] with the appropriate tag. Pull requests are always welcome :)

Enjoy.

[og]: https://github.com/tomhicks
[extension]: https://TBD
[twitter]: https://twitter.com/r4meau
[issues]: https://github.com/R4meau/plink-plonk/issues
[pixlr]: http://www.pixlr.com
[original-script]: https://gist.github.com/tomhicks/6cb5e827723c4eaef638bf9f7686d2d8
[network-feature-suggestion]: https://gist.github.com/tomhicks/6cb5e827723c4eaef638bf9f7686d2d8#gistcomment-3178223
[screenshotlink]: https://github.com/R4meau/plink-plonk/blob/master/doc-assets/plink-plonk-screenshot.png?raw=true
