Twitter Bootstrap ClassNames Completion (With Jade Support)
======================

手刻的浪漫

## About

Lightweight, not complex, hint, simply auto-completion. There are no complex snippets, it's just completions.

## Compatible

Tested on Sublime Text 2 Build 2220

## Features

Make your Sublime text editor auto-completion support Twitter bootstrap ClassNames inside html tag attr quoted and jade classes.


![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/1.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/2.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/3.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/4.jpg)

## API References

http://twitter.github.io/bootstrap/index.html

Version 2.3.2

## Installation

* Through the **Package control** to install.

  ![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/through_package_control_install.jpg)

* Waiting download from **Github**.

* Happy programming.

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