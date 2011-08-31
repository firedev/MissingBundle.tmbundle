# TextMate Missing Bundle  #
============================

## Ever felt like something is missing in Textmate? ##

We too, so here is The Missing Bundle for TextMate. Forked from Motion Commands, expanded and re-written. Now includes the following functionality:

* Put cursor at the beginning of code even in long lines with Cmd+Opt+←
* Cleans whitespace on save Cmd+S
* Delete the current line with Cmd+Opt+Del
* Delete entire current word with Opt+Del
* Download Texmate Missing Bundle on GitHub

## Installation ##

To install via Git:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/McArrow/MissingBundle.tmbundle.git
    osascript -e 'tell app "TextMate" to reload bundles'

Homepage - [firedev.com](http://firedev.com), 
Original idea - [motion_commands bundle](https://github.com/rwilcox/motion_commands.tmbundle)
