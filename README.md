Twitter Bootstrap ClassNames Completion
======================

**Tested on Sublime Text 2 Build 2220**

## About

Make your autocomplete support Twitter Bootstrap ClassNames Completion with in HTML tags.

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/1.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/2.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/3.jpg)

![](https://raw.github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/master/README/4.jpg)

## Installation

* [Download](https://github.com/Pleasurazy/Sublime-Twitter-Bootstrap-ClassNames/archive/master.zip).

* Place it within your `Packages` folder. Recommend path is `Packages/User/autocomplete/twitter-bootstrap.sublime-completions`.

* Happy coding.

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