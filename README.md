# Jade Theme for VS Code

[![Version](https://vsmarketplacebadge.apphb.com/version/etoler1841.jade-theme.svg)](https://marketplace.visualstudio.com/items?itemName=etoler1841.jade-theme)

![Preview](https://raw.githubusercontent.com/etoler1841/jade-theme/master/images/ss.png)

# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `Jade Theme`.
3. Click **Install** to install it.
4. File > Preferences > Color Theme > **Jade**
5. Optional: Use the recommended settings below for best experience

## Recommended Settings

```json
{
  // This is all that matters
  "workbench.colorTheme": "Jade",
  // Wes Bos recommends Operator Mono. It's $200 and you need to buy it to get the cursive. I personally like Victor
  // Mono, which is what's in the screenshot. You can get it here: https://rubjo.github.io/victor-mono/. Fira Code
  // iScript is my secondary option.
  "editor.fontFamily": "'Victor Mono', 'Fira Code iScript', Consolas, 'Courier New', monospace",
  "editor.fontSize": 13.5,
  "editor.lineHeight": 1.85,
  "editor.fontWeight": "bold"
}
```

## Colors

- Green: #194935
- Green Highlight: #1F6246
- Green Highlight2: #236D4E
- Green Links & Buttons: #00AA77
- Green Dark: #123827
- Yellow: #ffc600
- Pink: #ff6dbb

- Orange: #ff9d00

## Contributing

To work on the theme:

1. Clone this repo and open in VS Code
2. Run the extension. `View → Run`
3. Click `Launch Extension`. This will open up another VS Code Editor.
4. Make changes to `jade.json`. You will see changes reflected in the other editor that opened in step 3.

If you are making a Pull Request, please give me a screenshot of before/after!

## Deploying a new version

These are mostly notes for me.

1. Increment the version number in `package.json`
2. Run `npm run bundle`
3. Run `npm run publish`

## I don't like something

First, this theme is new so if something is funky, please open an issue. There are many languages and parts of VS Code I don't use, so let me know!

These are the things we have control over. If you would like to change something, you can either open a PR and see if I'd like it added, or override the colors in your own settings.json file.

https://code.visualstudio.com/docs/getstarted/theme-color-reference

## Check out the original Cobalt 2!

If green's not your thing, the original blue is pretty sweet too. (This wasn't supposed to rhyme. Oops.)

[The original Cobalt 2](https://github.com/wesbos/cobalt2-vscode)

## Thanks

Thanks to Wes Bos for doing 99.8% of the work on this theme.
