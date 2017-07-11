# Mapache for [Ghost](https://github.com/tryghost/ghost/) by GodoFredo

[![Ghost version](https://img.shields.io/badge/Ghost-0.11.x-brightgreen.svg?style=flat-square)](https://ghost.org/)
[![Node version](https://img.shields.io/node/v/uno-zen.svg?style=flat-square)](https://nodejs.org/en/)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://bit.ly/PayPal-GodoFredoNinja)

> Minimalist Material Design and Elegant theme for [Ghost](https://github.com/tryghost/ghost/).

### Free theme for Ghost

Hello, I created this theme Ghost to see how it works. It is available for free so you can use on your site. It is strictly forbidden commercial use. If you have any suggestions to improve the theme,  you can send me tweet to [@GodoFredoNinja](http://bit.ly/tw-GodoFredoNinja)


### 😃 To have updated the subject please help me with a small collaboration in [paypal](https://bit.ly/PayPal-GodoFredoNinja). I will thank you enormentene

[![](./documentation/donate.gif)](https://bit.ly/PayPal-GodoFredoNinja)

![](./documentation/mapache-screenshot.png)


## Demo
You can see a demo in my [blog](http://bit.ly/GodoFredoNinja-Mapache).

## Mapache Support for Web Browsers
Mapache supports the following web [browsers](http://caniuse.com/#search=flexbox)

## Featured
- Responsive layout
- Blog navigation
- Page 404 (Multiple faces emoticons)
- Page subscribe
- Pagination Infinite Scroll
- Cover images for blog, tag and author
- links to followers in social media
- Related Articles (6 articles)
- Video Post Format
- Image post Format
- 5 articles featured in the home of the page section sidebar
- 5 articles latest posts in the (author - tag - post) section sidebar
- 10 Tags in the sidebar
- Previous and next button in the Post
- Support for comments (Facebook or Disqus)
- Support for counter comments (Facebook or Disqus)
- Buttons to share the article
- Counter shared articles on Facebook
- YouTube, Vimeo, kickstarter -> Video Responsive
- Code syntax [Prismjs](http://prismjs.com/index.html) Supported all syntax.


## Simply Support for Web Browsers
Mapache supports the following web [browsers](http://caniuse.com/#search=flexbox)

### Replace Favorite Icon
Create an image icon with these dimensions with the name icon.png `192px * 192px` in Copy your new favorite icon to `./assets/images/icon.png`

## Theme development

Simply uses [Webpack](https://webpack.github.io/) as a build tool and [npm](https://www.npmjs.com/) to manage front-end packages.

### Font Icons
Icons generated by [Icomoon](https://icomoon.io/app/#/select) and import  `src/fonts/selection.json`

### Install dependencies

From the command line on your host machine (not on your Vagrant development box), navigate to the theme directory then run `yarn`:

```shell
# @ themes/simply
$ yarn
```

You now have all the necessary dependencies to run the build process.

### Build commands

* `yarn run start` — Compile assets when file changes are made, start Browsersync session
* `yarn run build` — Compile and optimize the files in your assets directory
* `yarn run build:production` — Compile assets for production

#### Additional commands

* `yarn run rmassets` — Remove your `assets/` folder
* `yarn run lint` — Run eslint against your assets and build scripts

### Using Browsersync

To use Browsersync you need to update `devUrl` at the bottom of `src/config.json` to reflect your local development hostname.

If your local development URL is `https://project-name.dev`, update the file to read:
```json
...
  "devUrl": "https://project-name.dev",
...
```

By default, Browsersync will use webpack's [HMR](https://webpack.github.io/docs/hot-module-replacement.html), which won't trigger a page reload in your browser.

## Mapache settings
To continue with the configuration [Read](https://github.com/godofredoninja/Mapache/blob/master/README.md)

### Credits
- [Normalize](https://necolas.github.io/normalize.css/)
- [Jquery.ghostHunter](https://github.com/jamalneufeld/ghostHunter)
- [Prismjs](http://prismjs.com/)
- [sticky-kit](https://github.com/leafo/sticky-kit)
- [jquery-lazyload](http://www.appelsiini.net/projects/lazyload)

## Copyright & License

Copyright (c) 2016 GodoFredo - Released under the [MIT license](LICENSE).
