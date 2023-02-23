# TheCore

This is the main TheCore home page and will have links to specific games that use TheCore.

An example of a good help page in Markdown: [https://github.com/bobo38/TheCoreLite/blob/master/README.md](https://github.com/bobo38/TheCoreLite/blob/master/README.md)

## StarCraft 2
### What is TheCore?

_TheCore_ is a hotkey setup for StarCraft 2 that aims to improve and simplify the execution of mechanics by optimizing efficiency, ergonomics and fluidity. While there is no globally objective answer on what would be the single best hotkey setup, and there's tons of pro players that have gotten proficient with different ideas and priorities, the latest updated version of _TheCore Plus_ resembles the community's best efforts to optimize a hotkey layout. 

Carefully crafted, updated and maintained by a dedicated community since 2010, _TheCore_ doesn't leave much up to chance. It has lots of inert functionality to make common in-game tasks and mechanics faster and easier to execute, and also batches up some commonly utilized commands together in easily reachable locations; all while  taking cross-race play into consideration. 

(These pros are already using _TheCore_: Plug plug plug)

### Features
- Ergonomic and efficient layout, with drastically reduced hand movement
- Quick access to all camera hotkeys
- Modern control group management
- Easy cross-race play
- Separate hotkey files for different keyboards (QWERTY, Dvorak, Colemak and different regions) 
- Campaign and Co-op support (JuicyJuuce version. Any reason not to just use this one?) 
- Support for other games

## FAQ

---

### How long will it take me to learn this?

It greatly depends on the quantity and quality of practice. If the player uses methods of Deliberate Practice, _TheCore_ can be learned in a week. However if a player decides to learn _TheCore_ by playing many games of Starcraft (200-300) with no particular focus in mind, a player can learn _TheCore_ in a month. There is a [detailed learning program](https://docs.google.com/spreadsheets/d/1LhbxeYdkukOzYw030qNYQgLI1p3WUAbSTiuy1emeJSc/edit?usp=sharing) in the google drive folder for those looking for the fastest way we know to learn it.

### What’s different about the Plus and Lite versions?
// Proposition to clean up this explanation and make it more concise

In short, they can be seen as two modular additions to TheCore layout that provides different tradeoffs between mechanical efficiency, and familiarity/intuitivety. While all versions of TheCore provide a hotkey setup with carefully placed hotkeys and commands, we provide you with options to choose which side of the keyboard you want to play on (*Lite* or regular), and whether to optimize the placement of modifiers in terms of efficiency, frequency of use, and full access to modifier combinations (*Plus* or not). 


#### Plus
*Plus* is simply a slight augmentation to TheCore. It doesn't change anything in the hotkey layout, apart from changing up the position of the modifier keys - done either on the registry level of your computer, or from a custom keyboard driver dependant on whether you have access to that. This is done for two main reasons: 
- To improve efficiency by prioritizing more commonly used in-game mechanics on more accessible keys
- To accommodate for easily inputting all modifier combination with a single finger (preferrably thumb) 


When _plus_ and _lite_ are used in conjunction, all modifier combinations can easily be pressed and reached with your thumb for right handed players. 

> [!WARNING] Difference between button and action names
> While learning Plus versions of _TheCore_ by reading through the documentation, be sure to keep your tongue in your mouth, and differentiate between the action you want to input (i.e. queue up commands or select all of a certain unit), and the key you are used to relating to the function. For example, while using _TheCore+_, shift-queuing actions is performed with the Menu-button on TheCore+. Currently this translating process might heighten the learning curve. 
> // A way to update the TheCore visualizer would drastically reduce the learning curve for Plus versions especially

// Add some of the helpful examples from below to illustrate

#### Lite
// ... some of the info from below

---
TheCore Plus is the most efficient and most unconventional layout, followed by TheCore and finally TheCore lite; the version in closest resemblance to how you are used to using your keyboard. 

Specifically:

- Weirdness Factor:
  - TheCore and TheCore Plus are located on the “weird” side of the keyboard.
    - The fingers rest on `JIOP` for right handed (mouse) players and `WERG` for left handed (mouse) players.
  - TheCore lite is on the “normal” side of the keyboard.
    - The fingers rest in either a FPS `WASD` setup or a `ASTD` touch typing setup.
- Efficiency Factor:
  - Since TheCore and TheCore Plus use the thumb to press Ctrl, Shift, and Alt; and there is a much larger gap between the thumb and index than the pinky and ring; TheCore lite has less options for fast keys.
    - While the most common functions are just as fast on lite as TheCore and plus, this quickly changes with lite at a disadvantage for the remainder of the functions
  
  - TheCore plus makes use of hotkey drivers to change the location of Ctrl, Shift, and Alt in order to put modifiers in priority order.
    - For example, control is extremely useful so we put it at the shift location. (fastest key press out of the modifiers)
      - Adding unit types to control groups is done by holding Ctrl, clicking on the unit of the type you want to add, and pressing the key with the corresponding control group.  Selecting unit types and add/steal to control group are the same modifier!
      - Controlling types of units
        - Quickly pulling back marines so mines can destroy banes
        - Target firing
        - Etc

### Which finger do I use to press this key?

#### Right hand finger map:

![Right Hand Finger Map](https://drive.google.com/uc?export=view&id=1uEk92cUR5dhWRDvE8D3SY1R-kfG0sgQe)

#### Left hand finger map:

![Left Hand Finger Map](https://drive.google.com/uc?export=view&id=1zr_CrQUTvrlIaVfzwx5ev4KuED6ObKGB)

### Why is my camera moving every time I press Alt?

Alt is set to "center on current selection" intentionally. The reason for this is that 7 cameras are dedicated base location cameras that will snap to your base whenever you want to shift+click back to minerals, do a transfer, or defend against a drop.  Our philosophy here is that by centering these cameras on a fixed point, it is easier to get the cursor in the desired location since the player already knows exactly where the mineral field (or other object) will be before moving the camera.

To create the camera where there is no building, simply hold down alt, and move the camera to the desired location after it has centered on selection (mini map is usually best for this). Alternatively, you can rebind Center on Selection. 

> [!WARNING] Important setting
> Make sure to go to "Options" -> "Gameplay" and uncheck "Smart camera pan". This will make sure that "Center on Selection" behaves properly by snapping immediately to the center, regardless of relative position of the selection (no sloppy camera panning). 

### How do I do larva injects with TheCore?

The primary suggestion is that camera locations are used to jump from base to base.  Whether or not injecting queens are on control group is personal preference, do what is best for you.

### What are the suggested use of control groups?

These are listed in [TheCore Spreadsheet](https://docs.google.com/spreadsheets/d/1zN7ufgH79t6uaCXorX6cs3mWfkMKFC_6VTtZ7vH_9-s/edit?usp=sharing) in the “Control Groups Cameras” tab.

### Ctrl+Shift+Alt+what?! How do I press that?

You have stumbled into a banished function!  Banished functions are set to Ctrl+Shift+Alt+key, this is to avoid conflicts with other functions.  Functions are banished when they are considered to form bad habits by default or if they’re considered unimportant/useless.

- For example, as awesome as the select all army button is, without proper guidance, it can put a new player into a mechanical rut that encourages them to use select all army instead of control groups.

### Ctrl+Shift+0 (or some other combination) is not working!

This problem has two major causes:

- Another program’s hotkey is interfering
  - Ctrl+Shift+0 is a default keyboard language switch hotkey.
  - Other programs have other default hotkeys that can conflict with Starcraft hotkeys.

- Another keyboard layout (such as a secondary language) is interfering
  - SC2 doesn’t play well with multiple typing layouts.  It will, seemingly at random, change languages mid game!  You can either remove the additional layouts, or learn your language switch hotkey so you can fix it quickly as it happens.

## Generic example section that can be removed:

### Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/TheCoreHotkeys/thecorehotkeys.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/TheCoreHotkeys/thecorehotkeys.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
