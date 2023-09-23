# File listing and documentation

## Important Javascript files

./manifest.json
./ui/wk.js
./ui/ui.min.js
./ui/options.min.js
./cs/sniffer.js
./cs/main.js
./com/taskdlg.min.js
./pop/sniffer.min.js
./pop/pop.min.js
./libs/mdl/mdc2.js
./bg/bg.min.js

## Important CSS files

./ui/options.min.css
./ui/ui.min.css
./com/taskdlg.min.css
./pop/pop.min.css
./pop/sniffer.min.css
./libs/mdl/material.indigo-lime.min.css

## Important html files

./about/en.htm
./ui/options.htm
./ui/index.htm
./help/en.htm
./com/taskdlg.htm
./pop/pop.htm
./pop/sniffer.htm
./bg/bg.htm

## Individual File documentation

### ./about/en.htm


### ./bg/bg.htm


### ./bg/bg.min.js

This file is a minified JavaScript file that is used in the background process of the application. It contains various functions and classes that handle different tasks such as database operations, task management, and communication with the UI. The file does not directly import any dependencies.

### ./com/taskdlg.htm


### ./com/taskdlg.min.css


### ./com/taskdlg.min.js


### ./cs/main.js


### ./cs/sniffer.js


### ./help/en.htm


### ./libs/mdl/material.indigo-lime.min.css


### ./libs/mdl/mdc2.js


### ./manifest.json

The manifest.json file is a configuration file that provides important information about the application to the Chrome browser. It includes fields such as the application's name, version, permissions, and more.

Here is a detailed explanation of each field:

- update_url: This field specifies the URL where the browser can check for updates to the application.
- manifest_version: This field specifies the version of the manifest file format.
- name: This field specifies the name of the application.
- short_name: This field specifies a shorter name for the application that can be used where space is limited.
- version: This field specifies the version of the application.
- description: This field provides a brief description of the application.
- icons: This field specifies the icons that should be used for the application in various contexts.
- default_locale: This field specifies the default locale for the application.
- minimum_chrome_version: This field specifies the minimum version of Chrome that the application requires.
- offline_enabled: This field indicates whether the application can work offline.
- homepage_url: This field specifies the URL of the application's homepage.
- externally_connectable: This field specifies the IDs of other extensions that the application can communicate with.
- permissions: This field specifies the permissions that the application requires.
- background: This field specifies the background page for the application.
- browser_action: This field specifies the default title, icon, and popup for the browser action.
- options_ui: This field specifies the options page for the application.
- content_scripts: This field specifies the content scripts that the application should inject into web pages.
- web_accessible_resources: This field specifies the resources that web pages can access.
- content_security_policy: This field specifies the content security policy for the application.

### ./pop/pop.htm


### ./pop/pop.min.css


### ./pop/pop.min.js


### ./pop/sniffer.htm


### ./pop/sniffer.min.css 


### ./pop/sniffer.min.js


### ./ui/index.htm


### ./ui/options.htm


### ./ui/options.min.css


### ./ui/options.min.js


### ./ui/ui.min.css


### ./ui/ui.min.js


### ./ui/wk.js


## File Tree



```tree.txt

.
├── about
│   ├── en.htm
│   └── zh.htm
├── bg
│   ├── bg.htm
│   ├── bg.min.js
│   └── chrono_testing.txt
├── com
│   ├── taskdlg.htm
│   ├── taskdlg.min.css
│   └── taskdlg.min.js
├── cs
│   ├── main.js
│   └── sniffer.js
├── documentation.md
├── fonts
│   ├── -2n2p-_Y08sg57CNWQfKNvesZW2xOQ-xsNqO47m55DA.woff2
│   ├── CWB0XYA8bzo0kSThX0UTuA.woff2
│   ├── ek4gzZ-GeXAPcSbHtCeQI_esZW2xOQ-xsNqO47m55DA.woff2
│   ├── Fcx7Wwv8OzT71A3E1XOAjvesZW2xOQ-xsNqO47m55DA.woff2
│   ├── flUhRq6tzZclQEJ-Vdg-IuiaDsNc.woff2
│   ├── KFOlCnqEu92Fr1MmEU9fABc4EsA.woff2
│   ├── KFOlCnqEu92Fr1MmEU9fBBc4.woff2
│   ├── KFOlCnqEu92Fr1MmEU9fBxc4EsA.woff2
│   ├── KFOlCnqEu92Fr1MmEU9fCBc4EsA.woff2
│   ├── KFOlCnqEu92Fr1MmEU9fChc4EsA.woff2
│   ├── KFOlCnqEu92Fr1MmEU9fCRc4EsA.woff2
│   ├── KFOlCnqEu92Fr1MmEU9fCxc4EsA.woff2
│   ├── md.css
│   ├── md-icons.css
│   ├── mErvLBYg_cXG3rLvUsKT_fesZW2xOQ-xsNqO47m55DA.woff2
│   ├── NdF9MtnOpLzo-noMoG0miPesZW2xOQ-xsNqO47m55DA.woff2
│   └── u0TOpm082MNkS5K0Q4rhqvesZW2xOQ-xsNqO47m55DA.woff2
├── help
│   ├── en.htm
│   └── zh.htm
├── icons
│   ├── bg
│   │   ├── 1.jpg
│   │   ├── 1-s.jpg
│   │   ├── 2.jpg
│   │   ├── 2-s.jpg
│   │   ├── 3.jpg
│   │   ├── 3-s.jpg
│   │   ├── 4.jpg
│   │   ├── 4-s.jpg
│   │   ├── 5.jpg
│   │   ├── 5-s.jpg
│   │   ├── 6.jpg
│   │   ├── 6-s.jpg
│   │   ├── 7.jpg
│   │   ├── 7-s.jpg
│   │   ├── 8.jpg
│   │   └── 8-s.jpg
│   ├── copy_opaque.png
│   ├── cws.png
│   ├── errorfile.png
│   ├── filetree
│   │   ├── directory.png
│   │   ├── file.png
│   │   ├── folder_open.png
│   │   └── spinner.gif
│   ├── language.png
│   ├── loading16.svg
│   ├── loading-alt.svg
│   ├── loading.svg
│   ├── logo
│   │   ├── 128.png
│   │   ├── 16.png
│   │   ├── 19.png
│   │   ├── 24.png
│   │   ├── 26.png
│   │   ├── 32.png
│   │   ├── 38.png
│   │   └── 48.png
│   ├── newd_pause.png
│   ├── newd.png
│   ├── noty
│   │   ├── file.png
│   │   ├── folder_open.png
│   │   ├── gear.png
│   │   ├── table.png
│   │   └── update.png
│   ├── panel-toggler.svg
│   ├── reddit.png
│   ├── sniffer
│   │   ├── edit.png
│   │   ├── img_loading.gif
│   │   ├── list.png
│   │   ├── loading.gif
│   │   ├── pause.png
│   │   ├── play.png
│   │   ├── slider.png
│   │   └── table.png
│   ├── tick.png
│   ├── tip.png
│   └── toolbar
│       └── toolbar.png
├── libs
│   ├── jquery-2.1.0.min.js
│   └── mdl
│       ├── material.indigo-lime.min.css
│       └── mdc2.js
├── _locales
│   ├── am
│   │   └── messages.json
│   ├── ar
│   │   └── messages.json
│   ├── bg
│   │   └── messages.json
│   ├── bn
│   │   └── messages.json
│   ├── ca
│   │   └── messages.json
│   ├── cs
│   │   └── messages.json
│   ├── da
│   │   └── messages.json
│   ├── de
│   │   └── messages.json
│   ├── el
│   │   └── messages.json
│   ├── en
│   │   └── messages.json
│   ├── en_GB
│   │   └── messages.json
│   ├── es
│   │   └── messages.json
│   ├── es_419
│   │   └── messages.json
│   ├── et
│   │   └── messages.json
│   ├── fa
│   │   └── messages.json
│   ├── fi
│   │   └── messages.json
│   ├── fil
│   │   └── messages.json
│   ├── fr
│   │   └── messages.json
│   ├── gu
│   │   └── messages.json
│   ├── he
│   │   └── messages.json
│   ├── hi
│   │   └── messages.json
│   ├── hr
│   │   └── messages.json
│   ├── hu
│   │   └── messages.json
│   ├── id
│   │   └── messages.json
│   ├── it
│   │   └── messages.json
│   ├── ja
│   │   └── messages.json
│   ├── kn
│   │   └── messages.json
│   ├── ko
│   │   └── messages.json
│   ├── lt
│   │   └── messages.json
│   ├── lv
│   │   └── messages.json
│   ├── ml
│   │   └── messages.json
│   ├── mr
│   │   └── messages.json
│   ├── ms
│   │   └── messages.json
│   ├── nl
│   │   └── messages.json
│   ├── no
│   │   └── messages.json
│   ├── pl
│   │   └── messages.json
│   ├── pt
│   │   └── messages.json
│   ├── pt_BR
│   │   └── messages.json
│   ├── ro
│   │   └── messages.json
│   ├── ru
│   │   └── messages.json
│   ├── sk
│   │   └── messages.json
│   ├── sl
│   │   └── messages.json
│   ├── sr
│   │   └── messages.json
│   ├── sv
│   │   └── messages.json
│   ├── sw
│   │   └── messages.json
│   ├── ta
│   │   └── messages.json
│   ├── te
│   │   └── messages.json
│   ├── th
│   │   └── messages.json
│   ├── tr
│   │   └── messages.json
│   ├── uk
│   │   └── messages.json
│   ├── vi
│   │   └── messages.json
│   ├── zh
│   │   └── messages.json
│   ├── zh_CN
│   │   └── messages.json
│   └── zh_TW
│       └── messages.json
├── manifest.json
├── _metadata
│   └── verified_contents.json
├── pop
│   ├── pop.htm
│   ├── pop.min.css
│   ├── pop.min.js
│   ├── sniffer.htm
│   ├── sniffer.min.css
│   └── sniffer.min.js
├── snds
│   ├── error.ogg
│   └── finish.ogg
└── ui
    ├── index.htm
    ├── options.htm
    ├── options.min.css
    ├── options.min.js
    ├── ui.min.css
    ├── ui.min.js
    └── wk.js

```