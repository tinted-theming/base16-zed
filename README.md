# base16-zed

A set of [tinted-theming](https://github.com/tinted-theming) scheme templates for
[zed](https://github.com/sharkdp/vivid). These
templates can be used with any compliant [Base16
builder](https://github.com/tinted-theming/base16-builder-go).

## Usage

Depending on the usage, there are three ways on how to use this:

### 1. Manual copy

If you are fine with manually copying the data to `~/.config/zed/themes`,
you can always clone the repo or download the code as a zip file!

### 2. Symlink

The repo can be cloned inside `~/.config/zed` and the themes folder symlinked:

```sh
git clone <url> ~/.config/vivid/<repo>
ln -s ~/.config/zed/<repo>/themes ~/.config/zed/themes
```

The `2.` method is the recommended way to use the themes,
as it makes it easier to keep the files up to date if any changes arise!
