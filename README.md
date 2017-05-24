# VeriPress Themes

This is a collection of official themes for [VeriPress](https://github.com/veripress/veripress).

Themes are in the other branches of this repo.

## How To Use

To install official themes (from this repo), just use the theme management sub-command:

```sh
veripress theme install theme-name
```

Here `theme-name` should be the name of the theme you want to install.

## Theme Table

| Theme | Preview | Notes |
| ----- | ------- | ----- |
| [default] | [Preview][default-preview] | Default theme designed for blogs. |
| [clean-doc] | [Preview][clean-doc-preview] | Default theme designed for docs. |
| [fenki] | [Preview][fenki-preview] | Default theme designed for wikis. |

[default]: https://github.com/veripress/themes/tree/default
[default-preview]: https://veripress.github.io/demo/
[clean-doc]: https://github.com/veripress/themes/tree/clean-doc
[clean-doc-preview]: https://veripress.github.io/docs/
[fenki]: https://github.com/veripress/themes/tree/fenki
[fenki-preview]: http://fenkipedia.cn/wiki/

## Third-party Themes?

VeriPress's theme management sub-command also allows you to install third-party themes on GitHub. For example if you want to install a theme in the GitHub repo `someone/the-theme`, you can just run the following command:

```sh
veripress theme install someone/the-theme
```

By default the repo's name will be used as the theme name in your local, which is `the-theme` in this case. If you want a custom name, run the following:

```sh
veripress theme install someone/the-theme --name name-you-want
```

## Update Themes

To update an installed theme, run:

```sh
veripress theme update the-theme
```

## More

For more information on theme management, see VeriPress's [documemtation](https://veripress.github.io/docs/) and `veripress theme --help` (All sub-commands' help messages can be accessed through `--help` flag).
