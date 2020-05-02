# Jasmine Theme for Spicetify :paintbrush:
> A Spotify desktop theme for [Spicetify](https://github.com/khanhas/spicetify-cli)

1. [Installation](#cd-installation)
2. [Screenshots](#framed_picture-screenshots)
3. [Customisation](#gear-customisation)
	- [Colours](#colours)
	- [Styling](#styling)
4. [Acknowledgements](#scroll-acknowledgements)

## :cd: Installation

First, download and extract this repository into your Spicetify `Themes/` folder.

> :warning: The following commands assume you extract the contents into `Themes/Jasmine/`!

For the **light** variant:
```bash
spicetify config current_theme Jasmine/Jasmine-Dark
```

For the **dark** variant:
```bash
spicetify config current_theme Jasmine/Jasmine-Light
```

## :framed_picture: Screenshots

| Light                                                                                                  | Dark                                                                                                 |
|:------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------:|
| ![](Jasmine-Light/screenshots/home.png?raw=true "Jasmine Light - Home page")                           | ![](Jasmine-Dark/screenshots/home.png?raw=true "Jasmine Dark - Home page")                           |
| ![](Jasmine-Light/screenshots/artist.png?raw=true "Jasmine Light - Artist page")                       | ![](Jasmine-Dark/screenshots/artist.png?raw=true "Jasmine Dark - Artist page")                       |
| ![](Jasmine-Light/screenshots/playlist.png?raw=true "Jasmine Light - Browsing a playlist")             | ![](Jasmine-Dark/screenshots/playlist.png?raw=true "Jasmine Dark - Browsing a playlist")             |
| ![](Jasmine-Light/screenshots/album.png?raw=true "Jasmine Light - Album")                              | ![](Jasmine-Dark/screenshots/album.png?raw=true "Jasmine Dark - Album")                              |
| ![](Jasmine-Light/screenshots/edit_playlist.png?raw=true "Jasmine Light - Editing a playlist")         | ![](Jasmine-Dark/screenshots/edit_playlist.png?raw=true "Jasmine Dark - Editing a playlist")         |
| ![](Jasmine-Light/screenshots/fullscreen.png?raw=true "Jasmine Light - Playing in full screen")        | ![](Jasmine-Dark/screenshots/fullscreen.png?raw=true "Jasmine Dark - Playing in full screen")        |
| ![](Jasmine-Light/screenshots/listening_on.png?raw=true "Jasmine Light - Listening on another device") | ![](Jasmine-Dark/screenshots/listening_on.png?raw=true "Jasmine Dark - Listening on another device") |

## :gear: Customisation

### Colours

If you're looking to tweak the primary colour, edit the colours under [`Jasmine-Dark/color.ini`](Jasmine-Dark/color.ini) or [`Jasmine-Light/color.ini`](Jasmine-Light/color.ini) depending on the theme you are using.

> :bulb: Checkout [coolors.co](https://coolors.co) to help picking colours

### Styling

This project uses [Sass](https://sass-lang.com/) to compile the final CSS files. Make changes to [`user.scss`](user.scss), compile it down to CSS and then overwrite the theme's `user.css` file.

> :bulb: Reference Spicetify's [wiki](https://github.com/khanhas/spicetify-cli/wiki)

## :scroll: Acknowledgements

- [Lovelace](https://github.com/morpheusthewhite/spicetify-themes/tree/master/Lovelace) Spicetify theme by [@adriankarlen](https://github.com/adriankarlen)
