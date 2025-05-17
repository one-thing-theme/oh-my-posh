# Oh My Posh (One Thing Theme)

_Modern, minimal & simple visual studio code theme that combine black, white and gray colors_

_Screenshots:_

![Light](https://cdn.hashnode.com/res/hashnode/image/upload/v1746692987949/878542fe-a4ab-45d8-b147-46cd51c84c3b.png)
![Dark](https://cdn.hashnode.com/res/hashnode/image/upload/v1747462300564/84490b4a-f79a-4db4-93d8-1b2f2487b6f8.png)

## Recomended settings

If you want to use this theme with all of the features and simplicity, you can start tweak the settings by following the [official guide](https://onethingtheme.vercel.app/docs)

## Installation

To install the theme for oh my posh, you can follow the step below.

1. Create the oh my posh theme folder in `~/.config/oh-my-posh`

```
mkdir ~/.config/oh-my-posh
```

2. Create the theme folder inside them,

```
cd ~/.config/oh-my-posh
mkdir themes
cd themes
```

3. Download the one thing themes for oh my posh.

```
curl -o one-thing.omp.json https://raw.githubusercontent.com/one-thing-theme/oh-my-posh/refs/heads/main/themes/one-thing.omp.json
```

4. Update the oh my posh config to use the theme. Inside the .zshrc file update the settings using.

```
# ZSH CONFIGURATION
# Oh My Posh configuration
if [ "$TERM_PROGRAM" != "Apple_Terminal" ]; then
  eval "$(oh-my-posh init zsh --config ~/.config/oh-my-posh/themes/one-thing.omp.json)"
fi

```
