# Leftwm Dotfiles

## Dependencies
- Leftwm
- Kitty
- Cava
```
paru -S leftwm kitty cava
```

## Fonts Required
- Hack Nerd Font

```
  paru -S ttf-hack-nerd
```

## Steps

```
git clone https://github.com/kiranraaj19/leftwm-dotfiles
cd leftwm-dotfiles/.config
ln -s kitty/ ~/.config/kitty
ln -s cava/ ~/.config/cava
ln -s starship.toml ~/.config/starship.toml
```
