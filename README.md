# Description

Tired of fancy pagan witticisms? Display a daily verse of God's eternal Truth on your desktop!

This is a variety plugin. You need to install [variety](https://github.com/varietywalls/variety) first to make it work.

This simple script fetches content from [BibleGateway](https://www.biblegateway.com), and it is possible to use any version the site supports (I've only tested three).

# How to use

Download the `verse.py` script and replace `version` with your preferred one. (Look up version codes [here](https://www.biblegateway.com/versions/), for example, the site lists "English Standard Version (ESV)", so the version code would be `ESV`.) Then copy the script to `$HOME/.config/variety/plugins/`. Restart `variety` and go to Preferences > Effects > Quotes > Sources and Filtering, uncheck all checkboxes except, of course, "Bible Gateway's Verse of the Day". Remove all tags and authors. Now it should work perfectly!

# Screenshots

![ESV](screenshots/ESV.png)

![CUV](screenshots/CUV.png)
