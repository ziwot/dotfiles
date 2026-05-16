# dotfiles

## Dependencies

- zsh
- fzf
- tmux
- ripgrep

## Installing

Run `stow` to symlink everything or just select what you want

```sh
stow */ -t ~/ # Everything (the '/' ignores the README)
```

```sh
stow zsh # Just my zsh config
```

```sh
stow -nv */ -t ~/ # simulation
```

### lf

The [lf](https://github.com/gokcehan/lf) config requires [kitty](https://sw.kovidgoyal.net/kitty/) and 
[pistol](https://github.com/doronbehar/pistol)to be installed, 
see [docs](https://github.com/gokcehan/lf/wiki/Previews#with-kitty-and-pistol)

### tmux

Install plugins with `prefix + I`

### conf

```sh
 npm config set prefix "${HOME}/.npm-packages"
```

## Resources

- <https://www.youtube.com/@teej_dv>
- <https://systemcrafters.cc>
- <https://www.lunarvim.org>
- <https://www.youtube.com/c/ThePrimeagen>
- <https://github.com/ChristianChiarulli/Machfiles>
- <https://www.davidbegin.com/how-i-use-tmux/>
- <https://github.com/Antonio-Bennett/lvim>
- <https://github.com/abzcoding/>
- <https://lukesmith.xyz/>
- <https://github.com/rwxrob>
- <https://git.sr.ht/~whynothugo/dotfiles/>
- <https://github.com/dreamsofcode-io/tmux>
- <https://afridi.dev/articles/organize-your-zsh-configurations-and-plugins/>
