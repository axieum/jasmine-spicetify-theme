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
spicetify config current_theme Jasmine color_scheme light
```

For the **dark** variant:

```bash
spicetify config current_theme Jasmine color_scheme dark
```

## :framed_picture: Screenshots

|                                             Light                                              |                                             Dark                                             |
| :--------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------: |
|              ![](screenshots/light/home.png?raw=true "Jasmine Light - Home page")              |              ![](screenshots/dark/home.png?raw=true "Jasmine Dark - Home page")              |
|            ![](screenshots/light/artist.png?raw=true "Jasmine Light - Artist page")            |            ![](screenshots/dark/artist.png?raw=true "Jasmine Dark - Artist page")            |
|       ![](screenshots/light/playlist.png?raw=true "Jasmine Light - Browsing a playlist")       |       ![](screenshots/dark/playlist.png?raw=true "Jasmine Dark - Browsing a playlist")       |
|               ![](screenshots/light/album.png?raw=true "Jasmine Light - Album")                |               ![](screenshots/dark/album.png?raw=true "Jasmine Dark - Album")                |
|     ![](screenshots/light/edit_playlist.png?raw=true "Jasmine Light - Editing a playlist")     |     ![](screenshots/dark/edit_playlist.png?raw=true "Jasmine Dark - Editing a playlist")     |
|    ![](screenshots/light/fullscreen.png?raw=true "Jasmine Light - Playing in full screen")     |    ![](screenshots/dark/fullscreen.png?raw=true "Jasmine Dark - Playing in full screen")     |
| ![](screenshots/light/listening_on.png?raw=true "Jasmine Light - Listening on another device") | ![](screenshots/dark/listening_on.png?raw=true "Jasmine Dark - Listening on another device") |

## :gear: Customisation

### Colours

If you're looking to tweak the colours, edit the relevant variant under the [`color.ini`](color.ini) file.

> :bulb: Checkout [coolors.co](https://coolors.co) to help picking colours

### Styling

This project uses [Sass](https://sass-lang.com/) to compile the final CSS files. Make any changes to [`user.scss`](user.scss), compile it down to CSS and then overwrite the theme's `user.css` file.

> :bulb: Reference Spicetify's [wiki](https://github.com/khanhas/spicetify-cli/wiki)

## :scroll: Acknowledgements

- [Lovelace](https://github.com/morpheusthewhite/spicetify-themes/tree/master/Lovelace) Spicetify theme by [@adriankarlen](https://github.com/adriankarlen)
