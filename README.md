"Robin website" example for the web style guide
===

This is just a proof of concept to show how the "web style guide" could be extended and used in a website.

[main.scss](main.scss) makes use of [robin-theme](https://github.com/nottrobin/robin-theme), which is a bower module which extends [my version of the web style guide](https://github.com/nottrobin/web-style-guide).

Usage
---

Here's how to demo the capabilities of "robin-theme":

``` bash
bower install https://github.com/nottrobin/robin-theme  # Install robin-theme and dependencies into "bower_components"
sass --update main.scss                                 # Compile main.css
```

Now read "main.css" and you'll see it contains the CSS for a customised ubuntudesign grid.
