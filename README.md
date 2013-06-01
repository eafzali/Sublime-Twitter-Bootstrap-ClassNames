Twitter Bootstrap ClassNames Completion
======================

## About

Lightweight, not complex, hint, simply completion. There are no complex snippets, it's just completions.

## Compatible

Tested on Sublime Text 2 Build 2220

## Features

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/1.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/2.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/3.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/4.jpg)

## Installation

*. Through the install package to install.

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/through_package_control_install.jpg)

*. Waiting for download from Github.

*. Happy programming.

## Relevant issues

> How to trigger classname tip when every typing?

Open file `Packages/User/Preferences.sublime-settings` or click `Setting - User` from menu. In my case, I just setup the `auto_complete_triggers` property as follow:

```json
  "auto_complete_triggers":
  [
    {
      "characters": "<>\"'-_qazwsxedcrfvtgbyhnujmikolpQAZWSXEDCRFVTGBYHNUJMIKOLP",
      "selector": "text, source, meta, string, punctuation, constant"
    }
  ],
```

It will active most of scope triggers and most of characters.