# Leftwm Dotfiles

## Screenshot

![leftwm-rice](https://user-images.githubusercontent.com/39441413/227709840-fb21ee7a-0883-4ec2-a5c7-98b63a55e647.png)

## Dependencies
- Leftwm
- Kitty
- Starship
- Cava
```
paru -S leftwm kitty cava starship
```

## Fonts Required
- Hack Nerd Font

```
  paru -S ttf-hack-nerd
```

## Steps

```
git clone https://github.com/kiranraaj19/leftwm-dotfiles
ln -s $(pwd)/dotfiles ~/.config/leftwm/themes/current
cd leftwm-dotfiles/.config
ln -s kitty/ ~/.config/kitty
ln -s cava/ ~/.config/cava
ln -s starship.toml ~/.config/starship.toml
ln -s config.ron ~/.config/leftwm/config.ron
```
