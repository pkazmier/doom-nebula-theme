# doom-nebula-theme
A pair of Doom Emacs themes based on the `doom-vibrant` theme with influences
from the [Modus](https://protesilaos.com/modus-themes/) themes.  Nebula makes
extensive use of the variable pitch font for heading faces in an attempt at
better typography.  As a result, it is important to pick complimentary fixed
width and variable width fonts.

## Installation
Copy the `doom-nebula-theme.el`, `doom-nebula-blue-theme.el` and `nebula.png`
file into your `$HOME/.doom.d/themes` directory.  Add the following lines to
your `~/.doom.d/config.el`:

```elisp
;; If you like the font in the screenshots, add these settings
(setq-default line-spacing 0.2)
(setq doom-font (font-spec :family "IBM Plex Mono Text" :size 12)
      doom-big-font (font-spec :family "IBM Plex Mono Text" :size 16)
      doom-variable-pitch-font (font-spec :family "IBM Plex Sans" :size 13)
      doom-font-increment 1)

;; Theme settings
(setq doom-theme 'doom-nebula  ; or doom-nebula-blue
      fancy-splash-image (concat doom-private-dir "themes/nebula.png"))

```

## Screenshots
Below are a handful of screenshots with the modes I use most in both color
variants.  The font used in the screenshots is [IBM
Plex](https://www.ibm.com/plex/)--my new favorite font.

### Agenda
![Agenda](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/agenda.png?raw=true)
![Agenda](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/agenda-blue.png?raw=true)

### Elisp
![Elisp](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/elisp.png?raw=true)
![Elisp](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/elisp-blue.png?raw=true)

### OrgMode
![OrgMode](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/orgmode.png?raw=true)
![OrgMode](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/orgmode-blue.png?raw=true)

### Python
![Python](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/python.png?raw=true)
![Python](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/python-blue.png?raw=true)

### Rust
![Rust](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/rust.png?raw=true)
![Rust](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/rust-blue.png?raw=true)

### GoLang
![GoLang](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/golang.png?raw=true)
![GoLang](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/golang-blue.png?raw=true)


