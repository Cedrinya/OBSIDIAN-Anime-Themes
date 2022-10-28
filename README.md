# OBSIDIAN Anime Themes

OBSIDIAN Version 1.0.3

Note: I will try to keep updating the Themes and I am looking forward to adding more in the future.

## Introduction

My inspiration for creating Themes for Obsidian came from the lack of decent ones on the internet that would let me change the background image, text color and other elements easily, so I made my own.

## How to use

Note: Every Theme I create expects you to have **Base color scheme** set to **Dark**. To change this, simply go to **Settings**, click on **"Appearance"**, go to **"Base color scheme"** and change it to **"Dark"**. Plugins are not supported, so if any of those change the UI, you have to fix it yourself.

If you just want to use the Themes I created, it's going to be rather simple:

Just download the ```.css``` file and copy it into your ```vault/.obsidian/snippets``` folder. 
If you don't manage to find the folder, you can also go to **Settings**, click on **"Appearance"** and scroll all the way down where you can find **"Open snippets Folder"**.

After that you just click on **"Refresh"** and tick the Theme you want to use and you're good to go!

## Create your own

Note: My goal with this section is to make it as easy as possible for total beginners to get started with CSS scripting so they won't get overwhelmed by the amount of information there is to learn. I'm only a beginner myself, so everything I say should be taken with a grain of salt (You won't be a CSS master after this but I just try to explain the variables and values you need to change to achieve your desired result).

To create your own Theme, first make a copy of one of mine in the ```vault/.obsidian/snippets``` directory. From here on out, you can simply open that copy with the CSS Editor of your choice and start the Scripting!

It's important to say that if you use any of my templates you have to keep in mind that some images are Horizontal Cropped and others are Vertical cropped. Due to the fact that they use different techniques to define their position on screen, this information can be very important. There is a good chance that your Background Image will be incorrectly positioned or rotated. To solve this issue, simply adjust the variables provided in the **2nd Table**, don't worry, it's not that difficult.

For every argument listed below, I suggest setting it to something absurd first to see what changes (That's the way I do it myself most of the time).

Darling in the Franxx - Zero Two Theme - Horizontal cropped Image
Chainsaw Man - Power Theme - Vertical cropped Image
(The Sidebar Image is always Vertical)

**Theme Color Palette**

|Argument|Example|Description|
|-|-|-|
|`--color-variable01`|red|Changes the Primary Text Color|
|`--color-variable02`|green|Changes the Secondary Text Color|
|`--color-variable04`|$0000FF|Changes most of the Collapse Indicators, Table Lines in Edit Mode, Gutter Elements|
|`--color-variable03_rgb`|0,0,255|Changes Table Lines in the Sidebar|
|`--color-variable03`|$FFFF00|Changes the Top-bar color as well as the Sidebar outlines|
|`--image-variable01`|https://i.imgur.com/removed.png|Changes the Graph Mode Image|
|`--image-variable02`|https://i.imgur.com/removed.png|Changes the Editor Mode Image|
|`--image-variable03`|https://i.imgur.com/removed.gif|Changes the Sidebar Image|

**Image Position**

|Argument|Example|Description|
|-|-|-|
|`position:`|fixed|Specifies the type of positioning method used for the Editor & Graph Mode Background Image|
|`background-size:`|cover|Defines the size of the Editor & Graph Mode Background Image|
|`transform:`|rotateY(180deg)|Rotates the Editor & Graph Mode Background Image|
|`transform-origin:`|70%|Sets the position for the Editor & Graph Mode Background Image|
|`background-position:`|50%|Sets the position for the Sidebar Background Image|
|`top:`|50px|Used with `position:` to set the placement of the Background|
|`left`|0|Used with `position:` to set the placement of the Background|
|`right`|0|Used with `position:` to set the placement of the Background|
|`bottom`|0|Used with `position:` to set the placement of the Background|

**Image Filter**

|Argument|Example|Description|
|-|-|-|
|`filter:`|blur(4px) brightness(75%) saturate(50%)|Applies graphical effects to the Background|
|`backdrop-filter`|blur(4px) brightness(75%) saturate(50%)|Applies graphical effects to the gray Sidebar Overlay|
|`opacity:`|0.75|Changes the opacity of of some elements|

## License

Refer to the LICENSE file.

## Credits

### Darling in the Franxx - Zero Two Theme:

Zero Two Sitting at Night GIF by [Sofia_11l](https://tenor.com/users/sofia_11l)

Zero Two Standing Pose IMG by [Unthrottled - Alex Simons](https://github.com/Unthrottled)

### Chainsaw Man - Power Theme:

Power & Denji Train GIF by [Myschf](https://tenor.com/users/myschf)

Power Standing Pose IMG by [Steve Pensando](https://villains.fandom.com/wiki/User:Steve_Pensando)
