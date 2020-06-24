# Hugo Material Design Icons Shortcode

Add Material Design Icons to your Hugo site ✨

Light, fast, without an huge iconfont.

## Installation

```bash
# In your Hugo site folder
# First, clone the theme into your Hugo site:
git clone https://github.com/mochaaP/hugo-shortcode-mdi themes/mdi
# Add Git submodule to your site so that you can keep icons up-to-date
git submodule add https://github.com/mochaaP/hugo-shortcode-mdi themes/mdi
# Then fetch the icons from npm (Do this in themes/mdi)
yarn
# or `npm install`
```

Change your first theme to `"mdi"` (toml in example):

```toml
theme = ["mdi", "theme", "another-theme"]
```

You are all set!

To update the icons, do `yarn` again.

## Usage

Just put `{{% mdi [icon] %}}` in your document and it will magically works!

## License

MIT. See `LICENSE` for more details.

Material Design Icons belongs to [@Templarian](https://github.com/templarian/) and Google, licensed under SIL.
