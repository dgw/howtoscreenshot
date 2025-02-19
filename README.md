# How to take a screenshot

Because after years of computing, some people just don't know how.

## Why have another "How to screenshot" website?

[take-a-screenshot](https://www.take-a-screenshot.org/)

Let's face it. That site is old and dated. It uses jQuery version 1.9, meaning it was created somewhere around early-mid 2013. It's bloated, making around 50 network requests per page (including analytics and share widgets, with even more once the ads load). The bottom of the screen is taken up by a cookie warning banner. It even has a nicely sized [terms of service](https://www.take-a-screenshot.org/en/terms.html) page, and more legal-ish information in the [about](https://www.take-a-screenshot.org/de/about.html) page.

All of this takes away from the fact that it's a website about taking a screenshot. It should be simple, tell you how to take a screenshot, then get out of your way.

That's the goal of this repository.

## Contributing

Contributions are welcome. Fork, make changes, create a Pull Request.

A few points to consider as you make changes:

- The site must work on mobile devices.
- The site must work offline (using service workers).
  - This should mostly just work with Workbox generating the service worker.
- The site must work without Javascript enabled.
  - Only scripts should be to register service worker, service worker itself, and analytics (in the future).
- Reduce network requests.
  - Don't use &lt;img/&gt; tags, use inline &lt;svg&gt; instead.

### Contributors

A big thank you to the following people for their contributions to this project:

- [@ExperiBass](https://github.com/ExperiBass): Adding instructions for GNOME screenshot to the Linux page
- [@dgw](https://github.com/dgw): Adding instructions for transferring screenshots off of Switch

### Things to work on

#### Features

- [ ] Better diagrams
- [ ] Translation
- [ ] Other keyboard layouts

#### Platforms

- [x] Windows
- [x] Mac
- [x] Linux (?)
- [x] Android
- [x] iOS
- [x] XBox
- [x] PS4
- [x] PS5
  - [ ] Images
- [x] Steam (?)
- [ ] Nintendo Switch
- [ ] Steam Deck
- [ ] 3rd party programs (?)
- [ ] Webpages (browser extension) (?)
