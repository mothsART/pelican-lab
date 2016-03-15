# Intro

This theme is inspired by (pelican-bootstrap3)[https://github.com/getpelican/pelican-themes/tree/master/pelican-bootstrap3] but extend.

# Require

using the **(i18n_subsites)[https://github.com/getpelican/pelican-plugins/tree/master/i18n_subsites]** plugin.

# Settings

To add css theme (on your pelicanconf.py) :

    #!bash
    CSS_THEMES = [
        {
            "name": "Thème classique (orange)",
            "path": "theme/css/orange.css",
            "default": True
        },
        {
            "name": "Thème océan (bleu)",
            "path": "theme/css/ocean.css"
        }
    ]

# Task List

## 0.1

- [x] supporting change CSS theme with a dropdown :
    - [x] 2 differents styles purpose : orange and blue
    - [x] style keep with a cookie and apply with javascript

## 0.2

- [ ] doc
- Plugin integration
    - [x] tipue_search
    - [x] tag_cloud
    - [ ] 
- [ ] I18n on all page and all supported plugin :
    - [ ] 404 page
    - [ ] tipue_search

## 1.0

- test on multi-browsers
