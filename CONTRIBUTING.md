# Introduction
Welcome to Spectre MOTD's preset repository! This system is a very powerful yet extremely simple way of allowing users to share their presets for anyone and everyone to use, all with the click of a button in-game. This document will outline the process of creating your own presets.

# Steps
Create a file in the root level of the repository, with all the others. It should be named as follows: `<name>.preset`, where `name` is the name of your theme in [kebab-case](http://wiki.c2.com/?KebabCase).

Then, paste in the following template:

```
Name: Your theme name
Author: Your name
(settings export)
```

Where `(settings export)` is the JSON string that was copied to your clipboard when you exported your configuration through the "theming" button at the bottom of the in-game settings menu (this is also printed out to the console). This must reside on its own single line, the very last line of the file. Submit a pull request, and if it gets accepted, your theme will shortly be available on every installation of Spectre MOTD. That's all there is to it - if you're still unsure of what to do, feel free to check out some other presets in the repo!
