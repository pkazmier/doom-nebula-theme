# doom-nebula-theme
Doom Emacs theme based on `doom-vibrant` theme with influence from the Modus themes.

## Installation
Copy the `doom-nebula-theme.el` and `nebula.png` file into your `$HOME/.doom.d/themes` directory.
Add the following lines to your `~/.doom.d/config.el`:

```elisp
;; Font settings
(setq doom-font (font-spec :family "Iosevka" :size 14)
      doom-big-font (font-spec :family "Iosevka" :size 20)
      doom-variable-pitch-font (font-spec :family "Iosevka Etoile" :size 12))

;; Theme settings
(setq doom-theme 'doom-nebula
      fancy-splash-image (concat doom-private-dir "themes/nebula.png"))

```

## Screenshots
Below are a handful of screenshots with the modes I use most.

### OrgAgenda
![Agenda](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/agenda.png?raw=true)

### Elisp
![Elisp](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/elisp.png?raw=true)

### OrgMode
![OrgMode](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/orgmode.png?raw=true)

### Racket
![Racket](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/racket.png?raw=true)

### Python
![Python](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/python.png?raw=true)

### GoLang
![GoLang](https://github.com/pkazmier/doom-nebula-theme/blob/main/screenshots/golang.png?raw=true)
