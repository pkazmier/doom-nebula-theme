# doom-nebula-theme
Doom Emacs themes based on `doom-vibrant` theme with influence from the Modus themes.

## Installation
Copy the `doom-nebula-theme.el`, `doom-nebula-blue-theme.el` and `nebula.png`
file into your `$HOME/.doom.d/themes` directory.  Add the following lines to
your `~/.doom.d/config.el`:

```elisp
;; Font settings
(setq doom-font (font-spec :family "Iosevka" :size 14)
      doom-big-font (font-spec :family "Iosevka" :size 20)
      doom-variable-pitch-font (font-spec :family "Iosevka Etoile" :size 12))

;; Theme settings
(setq doom-theme 'doom-nebula  ; or doom-nebula-blue
      fancy-splash-image (concat doom-private-dir "themes/nebula.png"))

```

## Screenshots
Below are a handful of screenshots with the modes I use most in both color variants:

### OrgAgenda
![Agenda](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/agenda.png?raw=true)
![Agenda](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/agenda-blue.png?raw=true)

### Elisp
![Elisp](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/elisp.png?raw=true)
![Elisp](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/elisp-blue.png?raw=true)

### OrgMode
![OrgMode](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/orgmode.png?raw=true)
![OrgMode](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/orgmode-blue.png?raw=true)

### Racket
![Racket](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/racket.png?raw=true)
![Racket](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/racket-blue.png?raw=true)

### Python
![Python](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/python.png?raw=true)
![Python](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/python-blue.png?raw=true)

### GoLang
![GoLang](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/golang.png?raw=true)
![GoLang](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/golang-blue.png?raw=true)
