# Lyra Cobalt

[![Ghost version](https://img.shields.io/badge/Ghost-3.x-brightgreen.svg)](https://github.com/TryGhost/Ghost)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg)](https://www.paypal.me/godofredoninja)
[![Buy Me A Coffee](https://img.shields.io/badge/-Buy%20Me%20A%20Coffee-%23FF813F)](https://www.buymeacoffee.com/GodoFredoNinja)

Hello :smile: ,Who likes the [Lyra](https://github.com/tryghost/lyra) theme, please raise your :raising_hand_man: :raising_hand_woman: hands. Great, I have good news for you, yes for you. I used my quarantine days to modify the [Lyra](https://github.com/tryghost/lyra) theme into a beautiful cobalt theme.

 If you have questions :question: send me a tweet [@GodoFredoNinja](https://goo.gl/y3aivK)

## My dear friend :pray: Please, help me with a small donation on [Paypal](https://www.paypal.me/godofredoninja) or [Here](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=Y7UB5Q8GVN3HN&source=url). with your help I will continue to update the theme

[![donate](https://user-images.githubusercontent.com/10253167/79540832-66e04680-804e-11ea-9baa-6cdd8cc63a34.gif)](https://www.paypal.me/godofredoninja)

:arrow_right: If you still don't have a **Hosting for your Ghost**. Use [Digital Ocean](https://m.do.co/c/710a27a3b3de) using my [referral link]((https://m.do.co/c/710a27a3b3de)) and you will get free a **$50 credit** to use in [Digital Ocean]((https://m.do.co/c/710a27a3b3de)). This way you will also be helping me.

![screenshot](https://user-images.githubusercontent.com/10253167/79540735-41ebd380-804e-11ea-80b0-6de095c4cb39.jpg)

## Featured

- All the characteristics of the [original theme](https://github.com/tryghost/lyra).
- Menu for Mobile and Tablet
- Code syntax [Prismjs](https://prismjs.com/index.html#supported-languages) Supported all syntax

## Instructions

1. [Download this theme](https://github.com/TryGhost/Lyra/archive/master.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file
3. Unzip the theme archive on your computer and locate the file called `routes.yaml`
4. Inside Ghost admin, go to the `Labs` settings area and scroll down until you see the `Custom Routes` section
5. Upload the `routes.yaml` from this theme

That's it! You now have a Ghost publication which supports free and paid memberships. If you need help, check out the <a href="https://ghost.org/docs/members/">Ghost members documentation</a> or chat with other Ghost users on <a href="https://forum.ghost.org">Ghost forum</a>.

## Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
$ yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/<theme-name>.zip`, which you can then upload to your site.

```bash
yarn zip
```

## PostCSS Features Used

- Autoprefixer - Don't worry about writing browser prefixes of any kind, it's all done automatically with support for the latest 2 major versions of every browser.
- Variables - Simple pure CSS variables
- [Color Function](https://github.com/postcss/postcss-color-function)

### Credits

- [Lyra - Original Theme](https://github.com/tryghost/lyra)
- [Prismjs](http://prismjs.com/)
- [Fonts](https://fonts.google.com/specimen/Source+Sans+Pro?sidebar.open&selection.family=Source+Sans+Pro:wght@400;600)
- [Safari Light - Mockup](https://www.uplabs.com/posts/safari-light-version)

## Copyright & License

Copyright (c) 2013-2020 Ghost Foundation & GodoFredo - Released under the [MIT license](LICENSE).
