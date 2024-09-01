# base16-zed

A set of [tinted-theming] scheme templates for [zed]. These templates
can be used with any compliant [Base16 builder].

## Usage

### 1. Symlink

The repo can be cloned inside `~/.config/zed` and the themes folder
symlinked:

```sh
git clone <url> ~/.config/zed/<repo>
ln -s ~/.config/zed/<repo>/themes ~/.config/zed/themes
```

Depending on the usage, there are three ways on how to use this:

### 2. Manual copy

If you are fine with manually copying the data to
`~/.config/zed/themes`, you can always clone the repo or download the
code as a zip file!

The `1.` method is the recommended way to use the themes, as it makes it
easier to keep the files up to date if any changes arise!

## TODO

Create a base16 extension for zed on this repo and make it available to
users using the store. An orientation can be the [material version of
gruvbox].

[tinted-theming]: https://github.com/tinted-theming
[zed]: https://zed.dev
[Base16 builder]: https://github.com/tinted-theming/tinted-builder-rust
[material version of gruvbox]: https://github.com/tokiory/zed-gruvbox-material
