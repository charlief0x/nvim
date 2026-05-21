# nvim

Personal Neovim config based on [LazyVim](https://lazyvim.github.io).

## Colorscheme

[dracula-pro-nvim](https://github.com/charlief0x/dracula-pro-nvim) — requires a [Dracula PRO](https://draculatheme.com/pro) license.

## Updating plugins

Run inside Neovim:

```
:Lazy update
```

Then commit the updated lockfile:

```sh
git add lazy-lock.json && git commit -m "Update plugins"
```
